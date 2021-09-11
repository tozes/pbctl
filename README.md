pbctl
=====

pbctl CLI

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/pbctl.svg)](https://npmjs.org/package/pbctl)
[![Downloads/week](https://img.shields.io/npm/dw/pbctl.svg)](https://npmjs.org/package/pbctl)
[![License](https://img.shields.io/npm/l/pbctl.svg)](https://github.com/tozes/pbctl/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g pbctl
$ pbctl COMMAND
running command...
$ pbctl (-v|--version|version)
pbctl/0.0.0 darwin-arm64 node-v14.16.0
$ pbctl --help [COMMAND]
USAGE
  $ pbctl COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`pbctl hello [FILE]`](#pbctl-hello-file)
* [`pbctl help [COMMAND]`](#pbctl-help-command)

## `pbctl hello [FILE]`

describe the command here

```
USAGE
  $ pbctl hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ pbctl hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/tozes/pbctl/blob/v0.0.0/src/commands/hello.ts)_

## `pbctl help [COMMAND]`

display help for pbctl

```
USAGE
  $ pbctl help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
