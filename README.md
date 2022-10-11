# TUM Marp Template

[![Actions Status](https://github.com/hofbi/tum-marp-template/workflows/CI/badge.svg)](https://github.com/hofbi/tum-marp-template)

This is a template repository for [Marp Slides](https://marp.app) with a TUM theme. Marp is a markdown presentation ecosystem that allows you to create slides by writing simple markdown.

You can find a live demo at https://hofbi.github.io/tum-marp-template/

Download the [PDF](https://hofbi.github.io/tum-marp-template/slide-deck.pdf).

## Setup

Follow the setup on the [Marp CLI repository](https://github.com/marp-team/marp-cli) or use our `docker-compose.yml`.

## Build

```shell
# Learn the CLI
docker compose run generate --help

# Generate slides
docker compose run generate --input-dir ./slides         # Generate html
docker compose run generate --input-dir ./slides --pdf   # Pdf
docker compose run generate --input-dir ./slides --pptx  # Powerpoint

# Fast Live Serve of the slides
docker compose up   # Access the slides on http://localhost:8080
```

## How To

- [Get Started](https://github.com/marp-team/marp)
- [Documentation](https://marpit.marp.app/)
- [CLI](https://github.com/marp-team/marp-cli)

## Paper

This template was created as part of the [Software Engineering Lab](https://www.ei.tum.de/en/lmt/teaching/software-engineering-laboratory/) presented in *2022 IEEE/ACM 4th International Workshop on Software Engineering Education for the Next Generation (SEENG)* [[PDF](https://ieeexplore.ieee.org/document/9814913)].
If you use our template please cite our paper.

```tex
@inproceedings{hofbauer_2022,
    title = {Teaching Software Engineering As Programming Over Time},
    booktitle = {IEEE/ACM 4th International Workshop on Software Engineering Education for the Next Generation},
    address = {Virtual Event},
    author = {Hofbauer, Markus and  Bachhuber, Christoph and  Kuhn, Christopher and  Steinbach, Eckehard},
    month = {May},
    year = {2022},
    pages = {1--8},
}
```
