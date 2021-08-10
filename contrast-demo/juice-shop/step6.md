To remediate the vuln we will need to update one line in the login.js file

Line 30 has the remediation fix. We need to uncomment this line by removing the "//".

Finally add a double slash "//" to the start of line 29 or delete all of line 30

Check your container is up and running:

`docker ps`{{execute}}

Copy the login.js file into the local filesystem so that you can edit it:

`docker cp juiceshop:juice-shop/routes/login.js .`{{execute}}

Open the file either by the terminal or the editor and notice where the vulnerability has been triggered. Make the fix by commenting out the offending line of code and un-commenting the line of code with the parameterization fix.

Copy the file back into the docker container:

`docker cp login.js juiceshop:juice-shop/routes/login.js`{{execute}}

Re-start the container:

`docker restart juiceshop`{{execute}}

The remediation is complete you will need to move the vulnerability in CONTRAST to a status of "remediated". Once that is complete try to re-trigger the sql injection as we did previously. The injection should fail and the status of the vulnerability in CONTRAST should remain as "remediated"

Congratulations you have remediated an SQL Injection vulnerability.
