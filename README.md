[![Build Status](https://travis-ci.org/nodeshift-starters/nodejs-rest-http-crud.svg?branch=master)](https://travis-ci.org/nodeshift-starters/nodejs-rest-http-crud) [![Coverage Status](https://coveralls.io/repos/github/nodeshift-starters/nodejs-rest-http-crud/badge.svg?branch=master)](https://coveralls.io/github/nodeshift-starters/nodejs-rest-http-crud?branch=master) [![Greenkeeper badge](https://badges.greenkeeper.io/nodeshift-starters/nodejs-rest-http-crud.svg)](https://greenkeeper.io/)

My Example CRUD Application

### Getting Started

#### Running on Openshift

First, make sure you have an instance of Openshift setup and are logged in using `oc login`.

Then create a new project using the `oc` commands

`oc new-project fun-node-fun`

For this example, you will also need a postgres db running on your Openshift cluster.

`oc create -f my-nodejs-postgresql-persistent.yaml`

Then you can navigate to the newly exposed route, something similar to "http://nodejs-rest-http-crud-boosters.192.168.99.100.nip.io/",  this will be different

