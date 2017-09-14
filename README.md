# Continuous Delivery Using Docker and Ansible
The main purpose of Docker is to create minimal environment for any purpose.
e.g. create a linux env to run a script, than drop the container.
To run the application build processes.

Continous Delivery(to successfully deliver applications faster and more reliably) using Docker and Ansible:

Continuous delivery workflow from scratch using Docker and Ansible allowing us to Test, Build, Release and continuously deploy an application to AWS.

How to build a production-class continuous delivery workflow / pipeline that you can apply to any application or platform using Docker and Ansible:
1. Take care of running unit and integration test.
2. Building application artifacts.
3. Creating docker release images and running acceptance test to verify external functionality.
4. Tag and publish each tested and verified docker release image.

Using docker will enable us to create a completely portable workflow that would first develop and run locally and then set up popular jenkins continuous delivery system we will configure integration with GitHub allowing the continuous dellivery workflow to be triggered on each application source code commit. Assuming the application passes all unit, integration and acceptance tests our pipeline will publish release images to docker hub which will be deployed to AWS using Ansible using Infrastructure as a code approach with AWS cloud formation and leveraging the AWS EC2 container service for running docker containers in production.

How to achieve continuous Delivery?
automated tests, automated creation of environments, automated deployments of releases into environments, automated monitoring 
