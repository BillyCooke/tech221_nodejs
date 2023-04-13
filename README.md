# Webservers and Nginx

## How do webservers work?
The purpose of a webserver is to store, process and deliver requested information to the user. Information is requested to the webserver using HTTP from a user and the webserver takes in the request and processes a response again via HTTP.

## What is NodeJS and what is it used for?
NodeJS is an open-source server that can run on multiple operating systems and it is used to create server-side web applications.

## Who uses NodeJS?

* Netflix used Node.JS to build their user interface and as a consequence it is almost two times faster to load up Netflix
* Trello use Node.JS because it has the capacity to hold many open connections at once. This is important as it is vital to have immediate updates in Trello and as Node.JS can hold multiple open connections this is possible
* NASA uses Node.JS to present their software as a collection of small services rather than an autonomous unit

## What are the dependencies of Node.JS?
There are multiple dependencies that Node.Js relies on and these can be separated into two main areas. Libraries and Tools.

### Libraries
* V8 provides a JavaScript engine
* Libuv provides mechanisms to handle multiple systems such as DNS and streaming
* llhttp is used to handle HTTP parsing
* c-ares
* OpenSSL provides implementations of cryptographic functions
* zlib

### Tools
* npm
* gyp
* gtest

## What is NPM?
NPM is a software registry that contains over 800,00 packages. It can be used to share software. It is free to use and does not require any registration.

## What is a Reverse Proxy?
A Reverse Proxy is an application that sits between the client and the webserver and forwards on the requests to the relevant server.