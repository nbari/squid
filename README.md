# squid
web proxy using squid

- Authenticate via username/password
- Restrict access via whitelist

Requirements
------------

Install from ports:

    security/py-htpasswd

Create user:

    htpasswd.py -c -b users nbari secret
