# TUM Marp Template

[![Build Status](https://travis-ci.org/hofbi/tum-marp-template.svg?branch=master)](https://travis-ci.org/hofbi/tum-marp-template)
[![Actions Status](https://github.com/hofbi/tum-marp-template/workflows/CI/badge.svg)](https://github.com/hofbi/tum-marp-template)

This is a template repository for [Marp Slides](https://marp.app) with a TUM theme. Marp is a markdown presentation ecosystem that allows you to create slides by writing simple markdown.

You can find a live demo at https://hofbi.github.io/tum-marp-template/

Download the [PDF](https://hofbi.github.io/tum-marp-template/slide-deck.pdf).

## Setup

We use [Marp](https://marp.app) to generate the slides from markdown. Follow the setup on their [website](https://github.com/marp-team/marp-cli) or use our `docker-compose.yml`.

## Build

```shell
# Learn the CLI
docker-compose run generate --help

# Generate slides
docker-compose run generate --input-dir ./slides         # Generate html
docker-compose run generate --input-dir ./slides --pdf   # Pdf
docker-compose run generate --input-dir ./slides --pptx  # Powerpoint

# Fast Live Serve of lecture slides
docker-compose up   # Access the slides on http://localhost:8080

# Serve any slides
docker-compise run serve --watch --server ./slides
```

## How To

- [Get Started](https://github.com/marp-team/marp)
- [Documentation](https://marpit.marp.app/)
- [CLI](https://github.com/marp-team/marp-cli)
