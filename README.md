dost
====

A CLI to help you automate life with kubernetes

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/dost.svg)](https://npmjs.org/package/dost)
[![Downloads/week](https://img.shields.io/npm/dw/dost.svg)](https://npmjs.org/package/dost)
[![License](https://img.shields.io/npm/l/dost.svg)](https://github.com/karan-kapoor90/dost/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g dost
$ dost COMMAND
running command...
$ dost (-v|--version|version)
dost/0.0.0 darwin-x64 node-v14.15.1
$ dost --help [COMMAND]
USAGE
  $ dost COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`dost goodbye [FILE]`](#dost-goodbye-file)
* [`dost hello [FILE]`](#dost-hello-file)
* [`dost help [COMMAND]`](#dost-help-command)

## `dost goodbye [FILE]`

```
USAGE
  $ dost goodbye [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/goodbye.ts](https://github.com/karan-kapoor90/dost/blob/v0.0.0/src/commands/goodbye.ts)_

## `dost hello [FILE]`

```
USAGE
  $ dost hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ dost hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/karan-kapoor90/dost/blob/v0.0.0/src/commands/hello.ts)_

## `dost help [COMMAND]`

```
USAGE
  $ dost help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
