# Elastic APM: PHP Agent

[![CircleCI](https://circleci.com/gh/wizaplace/elastic-apm-php-agent/tree/master.svg?style=svg)](https://circleci.com/gh/wizaplace/elastic-apm-php-agent/tree/master)
[![Version](https://img.shields.io/github/v/release/wizaplace/elastic-apm-php-agent)](https://circleci.com/gh/wizaplace/elastic-apm-php-agent/tree/master)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/wizaplace/elastic-apm-php-agent/graphs/commit-activity)

This is a community PHP agent for Elastic.co's [APM](https://www.elastic.co/solutions/apm) solution, supporting the `v2` Intake API. Please note: This agent is not officially supported by [Elastic](https://www.elastic.co/).

## Documentation
* [Installation](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/install.md)
* [Breaking Changes](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/breaking-changes.md)
* [Configuration](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/config.md)
* [Knowledgebase](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/knowledgebase.md)

## Examples
* [Agent Initialization](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/agent-init.md)
* [Basic Usage](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/basic-usage.md)
* [Capture Throwable](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/capture-throwable.md)
* [Spans](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/spans.md)
* [Parent Transactions](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/parent-transactions.php)
* [Metricset](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/metricset.php)
* [Getting the Server Info](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/server-info.php)
* [Distributed Tracing](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/distributed-tracing.md)
* [Converting debug_backtrace to a stack trace](https://github.com/philkra/elastic-apm-php-agent/blob/master/docs/examples/convert-backtrace.md)

## Tests
```bash
vendor/bin/phpunit
```

## Origin of the project
This project is a fork of [philkra/elastic-apm-php-agent](https://github.com/philkra/elastic-apm-php-agent)

