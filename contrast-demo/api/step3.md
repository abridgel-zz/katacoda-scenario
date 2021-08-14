
In your script find the response and app variables and see that they are making API calls utilizing endpoint URLS. For these calls to work they will require the ORGID and APPID. Add them now. Also update your parameters for severities to 'HIGH' on line 13.

Once complete try to run your script

`cd $HOME/scripts`{{execute}}

`python3 lab3.py`{{execute}}

Noticed the JSON that is returned in the payload. 
