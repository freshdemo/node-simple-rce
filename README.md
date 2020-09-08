## Simple Node app with an RCE

This content has been cloned from https://github.com/appsecco/vulnerable-apps/tree/master/node-simple-rce (Thank you!) to ensure a copy in maintained.

This is a simple Node app that is vulnerable to command injection via a flawed use of the eval statement.

You can set this up using docker as:
```
docker run -p 8080:8080 -d appsecco/node-simple-rce
```

Browse to the following link to begin:
[http://localhost:8080/?q='Test'](http://localhost:8080/?q='Test'
)

Exploitation and discussion at:
[http://ibreak.software/2016/08/23/nodejs-rce-and-a-simple-reverse-shell](http://ibreak.software/2016/08/23/nodejs-rce-and-a-simple-reverse-shell)


