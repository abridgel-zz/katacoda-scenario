
Configure the contrast_security.yaml file

Next we will create the contrast_security.yaml file and populate it with some values from the contrast platform

`cat << EOF > contrast_security.yaml
api:
  url: https://apptwo.contrastsecurity.com/Contrast
  user_name:
  api_key:
  service_key:
application:
  name: JuiceShop_Student##
  group: student##_group
EOF `{{execute}}

Login to the contrast portal 

https://apptwo.contrastsecurity.com

Find your 

1. Username
2. Service Key
3. Api Key

Populate the contrast_security.yaml file with these values. You can use the KataKoda Editor in the top right portion of this screen. To see /root/contrast in the directory structure and be able to access the YAML file, hit the 'Refresh Tree' button.

Replace JuiceShop_Student## with your student number for example if your student 10 your application name will be "WebGoat_Student10"


