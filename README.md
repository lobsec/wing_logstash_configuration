# Logstash Wing VX file
Here's the configuration file I did for logstash to parse Extreme Network VX/NX log 


### Please remember to change:
* in the ```input``` section the variables ```host``` and ```port```
* in the ```output``` section the variables ```host```, ```user``` and ```password```


### Please note
CA file certificate (```cacert```) must be readable by the user who runs logstash so please remember to:
* check the file permission (must be 660)
* check the user permission (eg: logstash.root)
