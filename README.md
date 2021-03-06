# TypeDoc

> Create api documentations for typescript projects.


## Installation

TypeDoc runs on Node.js and is available as an NPM package. You can install TypeDoc
in your project's directory as usual:

```shell
$ npm install typedoc --save-dev
```

Like the TypeScript compiler, TypeDoc comes with a binary that can be called from anywhere
if you install TypeDoc as a global module. The name of the executable is ``tsd``.

```shell
$ npm install typedoc --global
$ tsd
```


## Preview

If you want to know what a documentation created with TypeDoc looks like, head over
to the GitHub page of the project. It contains an api documentation of TypeDoc generated with
TypeDoc:

http://sebastian-lenz.github.io/typedoc


## Usage

TypeDoc accepts most of the command line arguments that the TypeScript compiler accepts. One major
difference is the fact that one may pass an entire directory instead of individual files to the documentation
generator. So in order to create a documentation for an entire project you simply type:

```shell
$ tsd --out path\to\documentation\ path\to\typescript\project\
```