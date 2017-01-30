# Komodo - Node Open Mining Portal

This is a Komodo mining pool based off of Node Open Mining Portal.

Forked from https://github.com/joshuayabut/z-nomp

#### Production Usage Notice
This is beta software. All of the following are things that can change and break an existing Z-NOMP setup: functionality of any feature, structure of configuration files and structure of redis data. If you use this software in production then *DO NOT* pull new code straight into production usage because it can and often will break your setup and require you to tweak things like config files or redis data. *Only tagged releases are considered stable.*

#### Requirements
* Coin daemon(s) ([https://github.com/jl777/komodo](https://github.com/jl777/komodo) and build latest version from source)
* [Node.js](http://nodejs.org/) v7+ ([follow these installation instructions](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager))
* [Redis](http://redis.io/) key-value store v2.6+ ([follow these instructions](http://redis.io/topics/quickstart))

##### Seriously
Those are legitimate requirements. If you use old versions of Node.js or Redis that may come with your system package manager then you will have problems. Follow the linked instructions to get the last stable versions.


[**Redis security warning**](http://redis.io/topics/security): be sure firewall access to redis - an easy way is to
include `bind 127.0.0.1` in your `redis.conf` file. Also it's a good idea to learn about and understand software that
you are using - a good place to start with redis is [data persistence](http://redis.io/topics/persistence).



**For a setup guide, please visit: https://github.com/xRobeSx/kmd-gpu-mining **
