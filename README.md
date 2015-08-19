# CSin3Students website
## Powered by NodeJS, ExpressJS, MongoDB, and Bootstrap.

## Setup

Homebrew can be used for dependency management on OS X almost efforlessly.
This guide uses homebrew to install MongoDB and NodeJS.
To install Homebrew:
```
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
To install Node:
```
$ brew install node
```
By default node is packaged with the node package manager NPM

Install Node and npm. Then run
```
$ npm install
```
NPM install installs all of the local node libraries defined in the package.json file

If you don't have MongoDB
```
$ brew install mongo
```
After installing create a db directory
```
$ sudo mkdir -p /data/db 
```
Run mongod to make sure everything is good:
```
$ mongod
```
If mongo fails for this reason:
```
2015-08-19T11:12:18.737-0600 I STORAGE  [initandlisten] exception in initAndListen: 98 Unable to create/open lock file: /data/db/mongod.lock errno:13 Permission denied Is a mongod instance already running?, terminating
```
run
```
$ sudo chown -R `id -u` /data/db
```

### Contributing
Clone the repository and push up a branch to this repository.
The best way to get setup is by checking out the development branch
and checking out your branch based on those changes.

#### Coming soon
A guide to get your development environment set up
