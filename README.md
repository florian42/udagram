# Udagram on k8s
> Instagram clone using microservices architecture pattern

[![Build Status](https://travis-ci.org/florian42/udagram.svg?branch=master)](https://travis-ci.org/florian42/udagram.svg?branch=master)

## Installation

You'll need to install docker https://docs.docker.com/install/. Open a new terminal within the project directory and run:

Build the images: docker-compose -f docker-compose-build.yaml build --parallel
Push the images: docker-compose -f docker-compose-build.yaml push
Run the container: docker-compose up

- Create all Kubernetes API objects within udacity-c3-deployment/k8s using kubectl create -f

## Development setup

- Node must be installed
- AWS RDS and S3 must be setup including an IAM User with corresponding permissions to access S3
- npm i express --save
- npm i ts-node-dev tslint typescript @types/bluebird @types/express @types/node --save-dev
- each service has to be ran using:
    - npm i
    - npm run dev

## Release History

* 0.0.1
    * Initial submission

## Meta

Florian Aumeier

[https://github.com/florian42/udagram](https://github.com/florian42/udagram)