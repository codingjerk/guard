# Guard
Command line utility to run tasks on file(s) change

## Dependencies

* python 3.x
* inotify-tools

## Installation

```sh
$ git clone ...
$ cd guard
$ sudo install guard /usr/bin
```

## Usage

```sh
$ guard <FILES TO WATCH*> -c <COMMAND> [-i <INIT>] [-s] [-m] [-v {0,1,2,3}]
```

As example:

```sh
$ guard **/*.coffee -sc npm test -i echo Guard started...
```
