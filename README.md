# artemis-kubernetes
A test project for deploying a trivial activemq-artemis application on Kubernetes using Helm


## Directory structure

### activemq-artemis

Contains the Helm chart for a simple artemis server instance with a service.
It keeps the artemis user and password in a secret and allows them to be initialized using values.

It uses the image created for the [artemis-openshift-example project](https://github.com/carbonin/artemis-openshift-example/tree/master/images/artemis).
This image is available on dockerhub [here](https://hub.docker.com/r/carbonin/manageiq-artemis/).
