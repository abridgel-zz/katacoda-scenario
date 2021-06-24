
Configure the contrast_security.yaml file

`cat << EOF > /root/contrast/contrast_security.yaml
api:
  url: https://apptwo.contrastsecurity.com/Contrast
  user_name:
  api_key:
  service_key:
application:
  name: WebGoat_Student##
  group: student##_group
agent:
  java:
    standalone_app_name: WebGoat_Student##
EOF `{{execute}}

Login to the contrast portal find your username, service key, and api key. Populate the contrast_security.yaml file with these values

Replace WebGoat_Student## with your student number for example if your student 10 your application name will be "WebGoat_Student10"

