# Docker Image with oraclelinux9 base image 

This repo was created in order to test ansible roles with molecule.

## Build it locally

  docker build -t oraclelinux9img .
  docker run --name oraclelinux9con -d -P oraclelinux9img
  docker exec -it oraclelinux9con bash

## Use it from dockerhub

    https://hub.docker.com/repository/docker/lotusnoir/ansible_molecule_test_images:oraclelinux9
