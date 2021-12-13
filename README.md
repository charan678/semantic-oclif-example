semantic-oclif-example
======================

example oclif project

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/semantic-oclif-example.svg)](https://npmjs.org/package/semantic-oclif-example)
[![Downloads/week](https://img.shields.io/npm/dw/semantic-oclif-example.svg)](https://npmjs.org/package/semantic-oclif-example)
[![License](https://img.shields.io/npm/l/semantic-oclif-example.svg)](https://github.com/https://github.com/charan678/semantic-oclif-example/semantic-oclif-example/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g semantic-oclif-example
$ semantic-oclif-example COMMAND
running command...
$ semantic-oclif-example (-v|--version|version)
semantic-oclif-example/1.0.4 linux-x64 node-v14.18.1
$ semantic-oclif-example --help [COMMAND]
USAGE
  $ semantic-oclif-example COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`semantic-oclif-example hello [FILE]`](#semantic-oclif-example-hello-file)
* [`semantic-oclif-example help [COMMAND]`](#semantic-oclif-example-help-command)
* [`semantic-oclif-example world [FILE]`](#semantic-oclif-example-world-file)

## `semantic-oclif-example hello [FILE]`

describe the command here

```
USAGE
  $ semantic-oclif-example hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ semantic-oclif-example hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/charan678/semantic-oclif-example/blob/v1.0.4/src/commands/hello.ts)_

## `semantic-oclif-example help [COMMAND]`

display help for semantic-oclif-example

```
USAGE
  $ semantic-oclif-example help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.10/src/commands/help.ts)_

## `semantic-oclif-example world [FILE]`

describe the command here

```
USAGE
  $ semantic-oclif-example world [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ semantic-oclif-example world
  hello world from ./src/hello.ts!
```

_See code: [src/commands/world.ts](https://github.com/charan678/semantic-oclif-example/blob/v1.0.4/src/commands/world.ts)_
<!-- commandsstop -->
