
Setup and Configure the contrast_security.yaml file

`cat << EOF > /opt/contrast/contrast_security.yaml
api:
  url: https://apptwo.contrastsecurity.com/Contrast
  username:
  api_key:
  service_key:
EOF `{{execute}}

Login to the contrast portal find your username, service key, and api key. Populate the contrast_security.yaml file with these values

