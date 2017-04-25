# OFS

## Setup

### Install Prerequisites

1. Install [Git](https://git-scm.com/downloads).

2. Install [Node.js](https://nodejs.org/en/download/current), preferably (7.x).

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
    npm install -g polymer-cli
```

### Make a Clone of the Project on your Machine

6. Clone the project and go into it's path.
```
    git clone https://github.com/Organic-Food-Store/ofs-client
    cd ofs-client
```

6. Install all the dependencies for the app:
```
    npm install
    bower install
```

### Start (serve) the App

This command serves the app at a basic localhost URL `[localhost:8080](localhost:8080)`:
```
    polymer serve -p 8080
```

Adding the `-o` flag opens the website automatically, but at a 404:
```
    polymer serve -o
```
Navigate to [localhost:8080](localhost:8080) to use the app.

Or use the same hosted app at [organic-food-store.firebaseapp.com](organic-food-store.firebaseapp.com).
