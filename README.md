# Linux Server Configuration

Udacity - Full Stack Web Developer Nanodegree - Linux Server Configuration Project.

This project will take a baseline installation of a Linux server, prepare it to host web applications, secure server from a number of attack vectors, install and configure a database server, and deploy one of your existing web applications onto it.

## Server Information
* #### IP Address - 13.250.34.14
* #### Port - 2200
* #### URL - [Hypebeast Catalog](http://ec2-13-250-34-14.ap-southeast-1.compute.amazonaws.com)


## Summary
### Server software/package installed
* finger
* apache2
* libapache2-mod-wsgi
* PostgreSQL
* pip
* virtualenv
* flask
* sqlalchemy
* mod_wsgi
* httplib2
* python requests
* oauth2client
* psycopg2
* sqlalchemy_utils
### Server configuration
* #### User Management
    * Add new user `grader`
    * Denied remote login from `root`
    * Give `grader` to run commands using `sudo`
* #### Security
    * Only allow connections for `SSH` (port 2200), `HTTP` (port 80), and `NTP` (port 123)
    * Denied `SSH`(port 22) 
    * Key-based `SSH` authentication is enforced
    * Updated all system packages
* #### Application Functionality
    * The web server responds on port 80
    * PostgreSQL has been configured to serve data
    * Web server has been configured to serve the Item Catalog application as a WSGI app.
## Author
* Dejnarong Lamleangpon - _Programmer_ - [Profiles](https://github.com/Dejnarong)
## Acknowledgments
* [Deploy Flask App on ubuntu](https://devops.profitbricks.com/tutorials/deploy-a-flask-application-on-ubuntu-1404/)
* [Give sudo access by visudo](https://www.computerhope.com/unix/visudo.htm)
* [PostgreSQL create user/database and add access](https://medium.com/coding-blocks/creating-user-database-and-adding-access-on-postgresql-8bfcd2f4a91e)
* Some installation guide (information) are taken from what I learned in the udacity course.
