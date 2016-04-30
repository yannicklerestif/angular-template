npm
===
node must first be installed, using apt-get or installer.
To ensure last version of npm is installed, run this :
    
    sudo npm install npm -g
If there is already a package.json, npm packages can be installed using :
    npm install
    
If there is no package.json, it can be created using :
    
    npm init
Then, dependencies can be added using :
    
    npm install --save-dev
    npm install --save
For a non-node project, --save-dev will almost allways be used.

BOWER :
