
Download the Contrast Agent

`mkdir /root/contrast`{{execute}}

`curl --fail --silent --location "https://repository.sonatype.org/service/local/artifact/maven/redirect?r=central-proxy&g=com.contrastsecurity&a=contrast-agent&v=LATEST" -o /root/contrast.jar`{{execute}}

`chmod 755 /root/contrast/contrast.jar`{{execute}}

Capture your IP address as we will need this later

`cat /etc/hosts | awk 'END {print $1}'`{{execute}}
