# generator-mjs
Yeoman generator for MeaningfulJS<sup>2</sup> (based on Angular 2).

This generator allows you to trivially create a new project by typing `yo mjs [project-name]`.

## Prerequisites

The MeaningfulJS<sup>2</sup> generator expects several OS-specific tools to be present:

* Git Command-Line -- https://git-scm.com/downloads
* Node 4.x -- https://nodejs.org/en/download

```
// Verify the OS-specific tools are installed
$ git --version
git version [x.y.z]

$ node --version
[a.b.c]
```


## Installation

Once the OS-specific tools are in place, you are ready to install the Node-specific tools.

```
// Install Bower
$ npm install bower -g

// Install Gulp
$ npm install gulp -g

// Install JSPM
$ npm install jspm -g

// Install Yeoman
$ npm install yo -g

// Install MJS Yeoman Generator
$ npm install generator-mjs -g
```

## Usage
```
// To create a new project
$ mkdir myapp
$ cd myapp
$ yo mjs myapp
```
