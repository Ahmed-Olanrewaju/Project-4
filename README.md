## MEAN STACK DEPLOYMENT TO UBUNTU IN AWS

Install NodeJs
Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine. Node.js is used in this tutorial to set up the Express routes and AngularJS controllers.

Update ubuntu

![`sudo apt update`](./Images/sudo-apt-update.png)

![`sudo apt upgrade`](./Images/sudo-apt-upgrade-.png)

![`sudo apt install -y nodejs`](./Images/sudo-apt-install-y-nodejs.png)

# Install MongoDB

MongoDB stores data in flexible, JSON-like documents. Fields in a database can vary from document to document and data structure can be changed over time. 

![`MongoDB stores data in flexible, JSON-like documents`](./Images/MongoDB-stores-data-in-flexible-JSON-like-documents.png)

![`sudo apt install -y mongodb`](./Images/sudo-apt-install-y-mongodb.png)

Verify that the service is up and running

![`sudo systemctl status mongodb`](./Images/sudo-systemctl-status-mongodb.png)

Install npm – Node package manager.

![`sudo apt install -y npm`](./Images/sudo-apt-install-y-npm.png)

![`sudo npm install body-parser`](./Images/sudo-npm-install-body-parser.png)

![`Books`](./Images/Books.png)

![`npm init`](./Images/npm-init.png)

![`server code`](./Images/server-code.png)

# INSTALL EXPRESS AND SET UP ROUTES TO THE SERVER

Install Express and set up routes to the server


![`sudo npm install express mongoose`](./Images/sudo-npm-install-express-mongoose.png)

![`Create a file named routes.js`](./Images/Create-a-file-named-routes-js.png)

![`create a folder named models`](./Images/create-a-folder-named-models.png)

Create a file named book.js

![`Create a file named book.js`](./Images/Create-a-file-named-book-js.png)

# Access the routes with AngularJS

AngularJS provides a web framework for creating dynamic views in your web applications

![`mkdir public && cd public`](./Images/mkdir-public-cd-public.png)

![`script.js file.`](./Images/script-js-file.png)

![`index.html file`](./Images/index-html-file.png)

![`node server.js`](./Images/node-server-js.png)

![`curl -s http://localhost:3300`](./Images/curl-s-http-localhost-3300.png)

Run curl -s http://169.254.169.254/latest/meta-data/public-ipv4 for Public IP address or curl -s http://169.254.169.254/latest/meta-data/public-hostname for Public DNS name

![`Public IP address, Public DNS name`](./Images/Public-IP-address-and-PublicDNS-name.png)

Web Book Register Application

![`Web Book Register Application`](./Images/Web-Book-Register-Application.png)

![`Book Register Application`](./Images/Book-Register-Application.png)