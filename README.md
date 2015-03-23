# Utility scripts for playing around with Weave and Docker

## Introduction

These are a set of quick scripts I use for some frequent day to day bits and
pieces. Feel free to fork and use.  

## Dig Weave

Quick wrapper script to dig a specific address that has been configured
with weave-dns. Currently only tested on Ubuntu.

`./dig-weave`

## Flush Vagrant Docker Processes

Kill all of all docker containers running on vagrant hosts in your current 
directory (just picks up vagrant status).

`./flushVagrantDockerPS`
