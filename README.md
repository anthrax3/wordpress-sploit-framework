#Wordpress Sploit Framework

###Version 0.2

##The project
Wordpress Sploit Framework was developed for the purpose to provide a framework which creates proof of concept when discovering vulnerability in Wordpress core or Wordpress plugin.  
Wordpress Sploit Framework is able to exploit the vulnerability.  
Wordpress Sploit Framework includes a web server for the operation of CSRF vulnerabilities.  
Wordpress Sploit Framework operates of CSRF, XSS and SQL vulnerabilities.

##How to use
Wordpress Sploit Framework is used with simple configuration files.  
In the exploits directory is stored the configuration files for exploits.  
In the payloads directory is stored the configuration files for payloads.  
In the plugins-available directory is stored the plugins files.  

```
WordPress Sploit Framework

Example: wordpress_sploit.py [Exploit] [Payload] [Target]

Help:
-p: List payloads
-e: List exploits
-Pe: List plugins enabled
-Pa: List plugins available
-Pen [PLUGIN]: Enable the plugin
-Pdis [PLUGIN]: Disable the plugin
-h: Print this help
```
