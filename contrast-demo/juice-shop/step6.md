To remediate the vuln we will need to update one line in the following file

`edit /root/juice-shop/build/routes/login.js`{{execute}}

Line 31 has the remediation fix. We need to uncomment this line by removing the "//".

Finally add a double slash "//" to the start of line 30 or delete all of line 30

The remediation is complete you will need to move the vulnerability in CONTRAST to a status of "remediated". Once that is complete try to re-trigger the sql injection as we did previously. The injection should fail and the status of the vulnerability in CONTRAST sshould remain as "remediated"

Congratulations you have remediated an SQL Injection vulnerability.
