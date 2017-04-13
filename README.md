# OFS

### Setup

##### Prerequisites

1. Install [Git](https://git-scm.com/downloads).

2. Install an [active LTS version of Node.js](https://github.com/nodejs/LTS) (4.x or 6.x). The current version (7.x) should work, but is not officially supported.

3. Update npm.
```
npm install npm@latest -g
```

4. Install the latest version of Bower.
```
npm install -g bower
```

5. Install Polymer CLI.
```
npm install -g polymer-cli@next
```

##### Make a clone of the project on your machine

    git clone https://github.com/Organic-Food-Store/ofs-client
    cd ofs-client
    
Then do the following commands:

    npm install
    bower install

### Start the server

This command serves the app at `http://localhost:8080` and provides basic URL
routing for the app:

    polymer serve --open
