<h1 align="center">OFS - Client</h1>

<p align="center">
  <a href="https://organic-food-store.firebaseapp.com" target="_blank">
    <img src="/images/logo.png" width="50%">
  </a>
</p>

<p align="center">The Independent Polymer Website hosted at <a href="https://organic-food-store.firebaseapp.com" target="_blank">Firebase</a>.</p>

## Setup

### Install Prerequisites

[![Verify Steps with Client & Server Setup Video](https://raw.githubusercontent.com/Organic-Food-Store/ofs-client/master/dev/Capture.PNG)](https://www.useloom.com/share/0130bb002fcf408a908689f09be91490 "Verify Steps with Client & Server Setup Video")
##### Verify below step results with Client & Server Setup Video above - We recommend playing the video at 1.25x speed.

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

## Using the Client

#### The [Hosted Client](organic-food-store.firebaseapp.com) can be opened up on both web and mobile devices, and here is a demo of the client usage:

[![Client Usage Video](https://raw.githubusercontent.com/Organic-Food-Store/ofs-client/master/dev/Capture2.PNG)](https://www.useloom.com/share/739067c114ad4c48ae03e894049d1407 "Client Usage Video")
##### Client Usage Video - Changes have been made to the client since the time of video recording.
