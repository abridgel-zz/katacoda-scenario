
Setup and Configure the contrast_security.yaml file

`cat << EOF > /opt/contrast/contrast_security.yaml
api:
  url: https://apptwo.contrastsecurity.com/Contrast
  username:
EOF `{{execute}}

Create an environemtn file for your keys

`cat << EOF > /opt/contrast/setup.sh
#! /bin/bash
export API__API_KEY=
export API__SERVICE_KEY=
EOF `{{execute}}

Login to the contrast portal find your keys and populate the setup.sh file with the
1. API_KEY
2. API_SERVICE_KEY

Also put the value of your username (usually in email format) into the /opt/contrast/contrast_security.yaml file
