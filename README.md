Vagrant for MEAN Stack
======================

Vagrant Development Environment for Kick-Starting Developing an application in the MEAN Stack.

## Prerequisites
  You must have [vagrant](http://www.vagrantup.com/) installed.
  You must have [virtualbox](https://www.virtualbox.org/wiki/Downloads) installed.

### Install vagrant vbguest plugin
      * vagrant plugin install vagrant-vbguest

### Quick Start
1. Clone the repo: `git clone https://github.com/SubrataBauri/vagrant-for-mean.git`
* Launch machines with `vagrant up` from clone'd folder.
* SSH to appserver via command `vagrant ssh appserver`
* Launch appserver from folder `/usr/local/src/mean/mytestapp` with command `node app.js`
* Navigate in browser to [Express Server](http://192.168.1.12:3000/) and you should see "Welcome to Express"
* That's it you have a base application using the MEAN Stack as coined by [Valeri Karpov](http://blog.mongodb.org/post/49262866911/the-mean-stack-mongodb-expressjs-angularjs-and)

#### Environment Details
    * MongoDb Server IP = 10.0.0.101
    * Application Server IP = 10.0.0.102
