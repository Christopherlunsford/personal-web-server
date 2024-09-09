# personal-web-server
My personal web server project. Sets up a simple Nginx web server on a Linux machine. SSL certificate using Lets Encrypt. 

## Steps

1. Clone the repositiory:
```bash
git clone https://github.com/Christopherlunsford/personal-web-server.git
```

2. Run the script

```CLI
cd my-web-server.sh
./setup_web_server.sh
```

3. Set up Certbot for SSL

```CLI
sudo certbot --nginx -d example.com
```


4. Enjoy!
