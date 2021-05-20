how to launch the server:
---------------------
Dependencies
---------------------
Node.js and npm
Ruby
Sass
Git
Cordova (Optional)
----------
Setup
---------
In a terminal/command prompt, navigate to where you'd like BonziWORLD to be placed and run the following:

git clone https://github.com/memcorp-mems/NoWORLD
cd NoWORLD
----------
Client
----------
cd src
npm install
grunt build_www
cd ..
---------
Server
---------
cd server
npm install
node index.js
--------------------
After this, NoWORLD will be accessible on port 3000. (http://localhost:3000/)