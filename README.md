# SMART Tutorial  
(forked from: https://github.com/cerner/smart-on-fhir-tutorial)

Run the tutorial here:
https://cerner.github.io/smart-on-fhir-tutorial

Description
------------
The SMART tutorial is intended to help developers quickly create a example smart app, register it with Cerner's code console, and test it against Cerner's sandbox. It is a [Slate](https://github.com/lord/slate) site hosted through GitHub Pages and includes a small example app in the source folder.

Getting Started
------------------------------

### Prerequisites

You're going to need:

 - Git Hub (for source controle and host you smart app)

### Getting Set Up locally, when using your own server

You're going to need:

 - Ruby

To run this tutorial locally:

```bash
$ bundle install
```

```bash
$ bundle exec middleman server
```
To deploy changes to the gh-pages branch:

```bash
$ ./deploy.sh
```
