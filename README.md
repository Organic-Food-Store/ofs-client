# OFS - Client

<img style="text-align: center;" src="https://raw.githubusercontent.com/Organic-Food-Store/ofs-client/master/images/logo.png" alt="OFS Logo">

![OFS Logo](https://raw.githubusercontent.com/Organic-Food-Store/ofs-client/master/images/logo.png)

The Independent Polymer Website hosted at [Firebase](organic-food-store.firebaseapp.com).

## Setup

### Install Prerequisites

1. Install [Git](https://git-scm.com/downloads).

2. Install [Node.js](https://nodejs.org/en/download/current), preferably (7.x).

3. Update npm.
```sh
    $ npm install npm@latest -g
```

4. Install the latest version of Bower.
```sh
    $ npm install -g bower
```

5. Install Polymer CLI.
```sh
    $ npm install -g polymer-cli
```

## Running Locally

### Make a Clone of the Project on your Machine

6. Clone the project and go into it's path.
```sh
    $ git clone https://github.com/Organic-Food-Store/ofs-client
    $ cd ofs-client
```

6. Install all the dependencies for the app:
```sh
    $ npm install
    $ bower install
```

### Start (serve) the App

This command serves the app at a basic localhost URL `localhost:8080`:
```sh
    $ polymer serve -p 8080
```

Adding the `-o` flag opens the website automatically, but at a 404:
```sh
    $ polymer serve -o
```
Navigate to [localhost:8080](http://localhost:8080) to use the app.

Or use the same hosted app at [organic-food-store.firebaseapp.com](organic-food-store.firebaseapp.com).

***Note: Whether local or hosted, the app will only use the [organic-food-store.herokuapp.com/api](https://organic-food-store.herokuapp.com/api) for all serverside calls.***
