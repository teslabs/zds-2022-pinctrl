# Deep dive into pin control in Zephyr

[![build](https://github.com/teslabs/zds-beamer-template/actions/workflows/build.yml/badge.svg)](https://github.com/teslabs/zds-beamer-template/actions/workflows/build.yml)
[![pdf](https://img.shields.io/badge/latest-pdf-blue)](https://github.com/teslabs/zds-2022-pinctrl/releases/latest)

This repository contains the slides for the "Deep dive into in control in
Zephyr" talk given at the Zephyr Development Summit 2022.

[![Video](http://img.youtube.com/vi/bcTekbGN-Pk/0.jpg)](http://www.youtube.com/watch?v=bcTekbGN-Pk "Deep Dive into Pin Control in Zephyr")

## Build

The slides are written using the `beamer` LaTeX class. They can be built
by running:

```shell
make
```

Build files can be cleaned by running:

```shell
make clean
```

## Lint and format

Slides can be linted for errors by running:

```shell
make lint
```

Additionally, slides can be automatically formatted using:

```shell
make fmt
```
