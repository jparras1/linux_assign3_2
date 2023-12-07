# as3p2-starter-f23

You will have to edit some of these files to get your web servers working.

The included backend server runs on port 8080, 127.0.0.1:8080

## Included material

- backend binary, hello-server
- frontend, index.html
- nginx configuration file, hello.conf
- service file for backend, hello-server.service
- config for setting up servers, cloud-config.yml
- example curl commands for testing your server, curl.md

## Directories where the files above goes to
- backend binary, hello-server goes to **/usr/local/bin**
- frontend, index.html goes to **/var/www/my-site**
- nginx configuration file, hello.conf goes to **/etc/nginx/sites-available** (symbolic link will be created at **/etc/nginx/sites-enabled**)
- service file for backend, hello-server.service goes to **/etc/systemd/system**
- cloud-config.yaml is entered during the creation of droplet in digitalocean

## Video Link
- https://youtu.be/IUia50fpW24

## Servers
- Load Balancer: http://24.199.68.225/
- Server 1 (web1): http://137.184.12.164/
- Server 2 (web2): http://137.184.10.162/