# go-cmdhelping

If you are beginning your journey with [Senzing],
please start with [Senzing Quick Start guides].

You are in the [Senzing Garage] where projects are "tinkered" on.
Although this GitHub repository may help you understand an approach to using Senzing,
it's not considered to be "production ready" and is not considered to be part of the Senzing product.
Heck, it may not even be appropriate for your application of Senzing!

## :warning: WARNING: go-cmdhelping is still in development :warning: _

At the moment, this is "work-in-progress" with Semantic Versions of `0.n.x`.
Although it can be reviewed and commented on,
the recommendation is not to use it yet.

## Synopsis

`go-cmdhelping` contains utility packages for working with
[viper](https://github.com/spf13/viper) and
[cobra](https://github.com/spf13/cobra)

[![Go Reference](https://pkg.go.dev/badge/github.com/senzing-garage/go-cmdhelping.svg)](https://pkg.go.dev/github.com/senzing-garage/go-cmdhelping)
[![Go Report Card](https://goreportcard.com/badge/github.com/senzing-garage/go-cmdhelping)](https://goreportcard.com/report/github.com/senzing-garage/go-cmdhelping)
[![License](https://img.shields.io/badge/License-Apache2-brightgreen.svg)](https://github.com/senzing-garage/go-cmdhelping/blob/main/LICENSE)

[![go-test-linux.yaml](https://github.com/senzing-garage/go-cmdhelping/actions/workflows/go-test-linux.yaml/badge.svg)](https://github.com/senzing-garage/go-cmdhelping/actions/workflows/go-test-linux.yaml)
[![go-test-darwin.yaml](https://github.com/senzing-garage/go-cmdhelping/actions/workflows/go-test-darwin.yaml/badge.svg)](https://github.com/senzing-garage/go-cmdhelping/actions/workflows/go-test-darwin.yaml)
[![go-test-windows.yaml](https://github.com/senzing-garage/go-cmdhelping/actions/workflows/go-test-windows.yaml/badge.svg)](https://github.com/senzing-garage/go-cmdhelping/actions/workflows/go-test-windows.yaml)

## Overview

`go-cmdhelping` is an opinionated use of
[viper](https://github.com/spf13/viper) and
[cobra](https://github.com/spf13/cobra).

Context variables are specified in a list of
[option.ContextVariable](option/option.go).

The `[]option.ContextVariable` list is processed by functions in the
[cmdhelper](cmdhelper) package.

## Use

See
[main.go](main.go)
for an example of use.

## References

1. [API documentation]
1. [Development]
1. [Errors]
1. [Examples]
1. Related artifacts:
    1. [DockerHub]
    1. [Helm Chart]

[API documentation]: https://pkg.go.dev/github.com/senzing-garage/template-go
[Development]: docs/development.md
[DockerHub]: https://hub.docker.com/r/senzing/template-go
[Errors]: docs/errors.md
[Examples]: docs/examples.md
[Helm Chart]: https://github.com/senzing-garage/charts/tree/main/charts/template-go
[Senzing Garage]: https://github.com/senzing-garage-garage
[Senzing Quick Start guides]: https://docs.senzing.com/quickstart/
[Senzing]: https://senzing.com/
