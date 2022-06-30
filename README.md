# NGINX OSS or Plus with Wallarm Inside
Introduction to Deploying Wallarm Nodes installed as a Dynamic Module in NGINX OSS or Plus

### Goals
* Install NGINX
* Create a trial account at wallarm.com
* Install the Wallarm dynamic module for NGINX
* Connect the filtering node to Wallarm Cloud
* Configure NGINX and Wallarm to provide API and Application Security
* Simulate attacks against the node with GoTestWAF
* Explore the Wallarm Cloud Dashboard

### How to use this document

To ensure understanding of every step, every line which is to be entered by the
user is preceded by `$>`. This is by design to pace the exercises and prevent
the ability to bulk copy and paste multiple lines at once.

## The Demo environment

This guide is designed to be completed on any system including your laptop

## Prerequisites

Root access to recent version of Ubuntu (deployed however you wish). This lab guide used the 20.04.4 Focal release.

Please reference the following documentation for the currently supported and recommended kernels:
https://docs.wallarm.com/waf-installation/nginx/dynamic-module/#2-add-wallarm-repositories

This lab guide will assume you have deployed Ubuntu and have access to the CLI and a web browser that has connectivity to the ubuntu machine
