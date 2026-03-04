# @Unity-Billal-mesloub/gitlab-config

[**semantic-release**](https://github.com/Unity-Billal-mesloub/semantic-release) shareable config to publish npm packages with [GitLab](https://gitlab.com).

[![Build Status](https://github.com/Unity-Billal-mesloub/gitlab-config/workflows/Test/badge.svg)](https://github.com/Unity-Billal-mesloub/gitlab-config/actions?query=workflow%3ATest+branch%3Amaster) [![npm latest version](https://img.shields.io/npm/v/@semantic-release/gitlab-config/latest.svg)](https://www.npmjs.com/package/@semantic-release/gitlab-config)
[![npm next version](https://img.shields.io/npm/v/@semantic-release/gitlab-config/next.svg)](https://www.npmjs.com/package/@semantic-release/gitlab-config)

## Plugins

This shareable configuration use the following plugins:

- [`@Unity-Billal-mesloub/npm`](https://github.com/Unity-Billal-mesloub/npm)
- [`@Unity-Billal-mesloub/gitlab`](https://github.com/Unity-Billal-mesloub/gitlab)

## Install

```bash
$ npm install --save-dev semantic-release @semantic-release/gitlab-config
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/Unity-Billal-mesloub/semantic-release/blob/main/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@semantic-release/gitlab-config"
}
```

## Configuration

See each [plugin](#plugins) documentation for required installation and configuration steps.
