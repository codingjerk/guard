# Guard
Command line utility to run tasks on file(s) change

## Dependencies

* inotify-tools

## Installation

```sh
$ git clone ...
$ cd guard
$ sudo install -d /usr/bin guard
```

## Usage

```sh
$ guard <COMMAND> <FILES TO WATCH*>
```

As example:

```sh
$ guard 'npm test' **/*.coffee
```
