
Start WebGoat with Contrast:

Congratulations you are now ready to bring up the WebGoat application and start doing some IAST

Let's start the Contrast Agent with the WebGoat Server

`java -Dcontrast.config.path=/root/contrast/contrast_security.yaml -javaagent:/root/contrast/contrast.jar -jar /root/WebGoat/webgoat-server/target/webgoat-server-8.2.1-SNAPSHOT.jar --server.port=8080 --server.address=[[HOST_IP]]`{{execute}}

Once your application is up and running you can browse to the app at:

http://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/WebGoat

Or you can click on the WebGoat tab under the KataCoda Editor
