
Step2: Update the endpoints with the correct ORGID and APPID 

By now you should have an idea of how to utlize the API playground. You may leverage it to try and test endpoints but first you willneed your appid and orgid.

To find this navigate to your application in Contrast. Your url should be in the following form

https://apptwo.contrastsecurity.com/Contrast/static/ng/index.html#/16edc280-2c89-49a3-8378-ff35b1e00e22/applications/b28b5a91-5635-485c-bd9c-1bad7ada61aa

In this case the ORGID is the string following the /Contrast/static/ng/index.html# portion of the url. The APPID is the string following the /applications portion of the URL.

Here we see:

ORGID=16edc280-2c89-49a3-8378-ff35b1e00e22
APPID=b28b5a91-5635-485c-bd9c-1bad7ada61aa

Save your ORGID and APPID as you will need it to update your python script
