# python3-ssl-webserver
A quick solution to have a python webserver with SSL option configured from cloudflare

### Start a Secure Web Server with CloudFlare SSL

#### Tools:
- Server with ubuntu (commit if it works with other OSes)
- Python3 (check if you have it already with python3 ––version)
- CloudFlare account
- Domain name which has SSL activated with CloudFlare NameServers

Download SSL Certificate PEM and KEY

Go to CloudFlare Dashboard > SSL > Origin Server and Create Certificate

Copy PEM and KEY into a file named cert-and-key.pem* one after the other

Use the biscuit file web-server.py* anywhere you want to start server from
	
Check the path of the PEM file that created from CloudFlare certificate

Then run it with ``sudo python3 web-server.py``

Have a meditation session.

###### (*) String is optional
