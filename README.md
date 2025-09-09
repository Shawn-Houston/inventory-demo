My Example CRUD Application

### Getting Started

#### Running on Openshift

First, make sure you have an instance of Openshift setup and are logged in using `oc login`. An internal registry must be installed and working.

Then create a new project using the `oc` commands

`oc new-project fun-node-fun`

Then

`oc create -f my-nodejs-postgresql-persistent.yaml`


