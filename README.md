# Terminus acme Plugin

[![Terminus v2.x - v3.x Compatible](https://img.shields.io/badge/terminus-2.x%20--%203.x-green.svg)](https://github.com/pantheon-systems/terminus-plugin-example/tree/2.x)

A simple plugin for Terminus-CLI to get ACME and verify it.

Adds commands 'https:acme:dns-file' and 'https:acme:dns-txt' to Terminus. Learn more about Terminus Plugins in the
[Terminus Plugins documentation](https://pantheon.io/docs/terminus/plugins)

## Configuration

These commands require no configuration

## Usage
* `terminus https:acme:dns-file <site>.<env> example.com`
* `terminus https:acme:dns-txt <site>.<env> example.com`

## Installation

To install this plugin using Terminus 3:
```
terminus self:plugin:install c4rl1t0/terminus-acme-plugin
```

## Testing
This example project includes four testing targets:

* `composer lint`: Syntax-check all php source files.
* `composer cs`: Code-style check.
* `composer unit`: Run unit tests with phpunit
* `composer functional`: Run functional test with bats

To run all tests together, use `composer test`.

Note that prior to running the tests, you should first run:
* `composer install`
* `composer install-tools`

## Help
Run `terminus help https:acme` for help.
