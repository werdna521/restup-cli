RESTup CLI
===========

RESTup PHP&#39;s cli (command line interface) to speed up API development with RESTup Framework

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/restup-cli.svg)](https://npmjs.org/package/restup-cli)
[![Downloads/week](https://img.shields.io/npm/dw/restup-cli.svg)](https://npmjs.org/package/restup-cli)
[![License](https://img.shields.io/npm/l/restup-cli.svg)](https://github.com/codenitiva/restup-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g restup-cli
$ restup COMMAND
running command...
$ restup (-v|--version|version)
restup-cli/1.0.13-alpha win32-x64 node-v14.4.0
$ restup --help [COMMAND]
USAGE
  $ restup COMMAND
...
```
<!-- usagestop -->
```sh-session
$ npm install -g restup-cli
$ restup COMMAND
running command...
$ restup (-v|--version|version)
restup-cli/1.0.11-alpha win32-x64 node-v14.4.0
$ restup --help [COMMAND]
USAGE
  $ restup COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`restup controller NAME`](#restup-controller-name)
* [`restup help [COMMAND]`](#restup-help-command)
* [`restup init`](#restup-init)
* [`restup middleware NAME`](#restup-middleware-name)
* [`restup model NAME`](#restup-model-name)
* [`restup router NAME`](#restup-router-name)
* [`restup start [NAME]`](#restup-start-name)
* [`restup update [CHANNEL]`](#restup-update-channel)

## `restup controller NAME`

create a RESTup controller

```
USAGE
  $ restup controller NAME

ARGUMENTS
  NAME  name of the controller

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\controller.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.13-alpha/src\commands\controller.ts)_

## `restup help [COMMAND]`

display help for restup

```
USAGE
  $ restup help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.1.0/src\commands\help.ts)_

## `restup init`

initialize restup config files on existing restup project

```
USAGE
  $ restup init

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\init.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.13-alpha/src\commands\init.ts)_

## `restup middleware NAME`

create a RESTup Middleware

```
USAGE
  $ restup middleware NAME

ARGUMENTS
  NAME  name of the middleware

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\middleware.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.13-alpha/src\commands\middleware.ts)_

## `restup model NAME`

create a RESTup Model

```
USAGE
  $ restup model NAME

ARGUMENTS
  NAME  name of the model

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\model.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.13-alpha/src\commands\model.ts)_

## `restup router NAME`

create a RESTup router

```
USAGE
  $ restup router NAME

ARGUMENTS
  NAME  name of the router

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\router.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.13-alpha/src\commands\router.ts)_

## `restup start [NAME]`

create a restup project

```
USAGE
  $ restup start [NAME]

ARGUMENTS
  NAME  name of your project (default: restup-project)

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\start.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.13-alpha/src\commands\start.ts)_

## `restup update [CHANNEL]`

update the restup CLI

```
USAGE
  $ restup update [CHANNEL]
```

_See code: [@oclif/plugin-update](https://github.com/oclif/plugin-update/blob/v1.3.10/src\commands\update.ts)_
<!-- commandsstop -->
* [`restup controller NAME`](#restup-controller-name)
* [`restup help [COMMAND]`](#restup-help-command)
* [`restup middleware NAME`](#restup-middleware-name)
* [`restup model NAME`](#restup-model-name)
* [`restup router NAME`](#restup-router-name)
* [`restup update [CHANNEL]`](#restup-update-channel)

## `restup controller NAME`

create a RESTup controller

```
USAGE
  $ restup controller NAME

ARGUMENTS
  NAME  name of the controller

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\controller.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.11-alpha/src/commands/controller.ts)_

## `restup help [COMMAND]`

display help for restup

```
USAGE
  $ restup help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.1.0/src\commands\help.ts)_

## `restup middleware NAME`

create a RESTup Middleware

```
USAGE
  $ restup middleware NAME

ARGUMENTS
  NAME  name of the middleware

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\middleware.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.11-alpha/src/commands/middleware.ts)_

## `restup model NAME`

create a RESTup Model

```
USAGE
  $ restup model NAME

ARGUMENTS
  NAME  name of the model

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\model.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.11-alpha/src/commands/model.ts)_

## `restup router NAME`

create a RESTup router

```
USAGE
  $ restup router NAME

ARGUMENTS
  NAME  name of the router

OPTIONS
  -h, --help  show CLI help
```

_See code: [src\commands\router.ts](https://github.com/codenitiva/restup-cli/blob/v1.0.11-alpha/src\commands\router.ts)_

## `restup update [CHANNEL]`

update the restup CLI

```
USAGE
  $ restup update [CHANNEL]
```

_See code: [@oclif/plugin-update](https://github.com/oclif/plugin-update/blob/v1.3.10/src\commands\update.ts)_
<!-- commandsstop -->
