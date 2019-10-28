# ansible-role-dokuwiki
Deploy and update Dokuwiki

Things to note about this repository:

- don't blindly deploy it without understanding how it works and testing it for your environment
- it is currently only used on Ubuntu 18.04 LTS, so may not work on other versions
- there is currently no real error checking, this is experimental at this stage so treat it with caution
- you will need to download _dokuwiki-stable.tgz_ from https://www.dokuwiki.org/ and place it in the files directory
- don't forget to customise the variables for your setup

Variables used:
- webroot: this is the root directory for the website
- webowner: this is user the web server runs as to set the owner of the web directory and files
- webgroup: this is the group for the web server directory and files
- domain: this is the domain the website is hosted under
- subdomain: the is the sub-domain the website is hosted under
- wiki_ipv4: the IPv4 address the website is hosted on
- wiki_ipv6: the IPv6 address the website is hosted on

@aptanet  
Paul Tansom  
2019-10-28  
