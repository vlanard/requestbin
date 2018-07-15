# Self-hosted local RequestBin
This is a fork of the wonderful but discontinued public [RequestBin](https://github.com/Runscope/requestbin).

**This version lets you host your own requestb.in on your dev box without Heroku or Docker**!


* Original Creator: [Jeff Lindsay](http://progrium.com)
* License:  MIT
* Compatibility: Only tested on MacOS.

## Prerequisites

* python 2
* git
* pipenv : the glorious one-stop replacement for pip and virtualenv. More info: https://docs.pipenv.org/

    `$ brew install pipenv`

## One-Time Setup
- Download code:

    `$ git clone git://github.com/vlanard/requestbin.git`

- Install app dependencies & virtual env

    `$ pipenv install --python 2.7`

## Running Requestb.in

#### To start:

	$ pipenv shell
	$ python web.py

Open in a browser: http://localhost:4000/

Your own private RequestBin will be running on this server.

#### To stop:

* `Ctrl-C` to exit program
* `$ exit` to quit pipenv


