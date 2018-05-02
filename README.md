# Udacity Linux Server Configuration 

Take a baseline installation for linux server and run your application on it in a secured way.
  - IP address : 34.242.31.34
  - ssh port : 2200
  - Application URL: http://ec2-34-242-31-34.eu-west-1.compute.amazonaws.com

# Required Installed Softwares
  - Apache2
  - mod_wsgi
  - postgresql
  - Flask
  - httplib2
  - oauth2client
  - sqlalchemy
  - psycopg2
  - sqlalchemy_utils
  

# Steps :

  - login with ssh
  - create grader user
  - add the user to sudoers
  - update installed packages
  - change the port from 22 to 2200
  - make firewall allow only ssh with 2200 port
  - clone your project
  - rename your project file to __init__.py
  - install wzgi
  - configure appache services
  - install dependencies for your application


# Third Party Resources made use :

[rrjoson](https://github.com/rrjoson/udacity-linux-server-configuration)
