# Firewall-as-service
Firewall-as-service


### Howto install ###

In first time you need to Download and install Node.js

### Howto use ###

* Clone repository:
```bash
git clone https://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@github.com/BlackCounter/Firewall-as-service.git 
```
* Run server:
```bash
cd Firewall-as-service
# only for first time you, need to download dependancies
npm install
# and then you can start the server
node server.js
```
* Open browser and goto http://127.0.0.1:1337/

### Howto create own theme ###

* cd ./tpl/styles/
* open and change config.scss
* compile: scss --sourcemap=none style.scss ../theme/MyTheme.css
* select theme in Settings->Theme

### Default user and password ###

User: admin
Pass: (empty)
