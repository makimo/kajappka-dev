# Kajappka Dev Environment

This repository contains local development environment for Kajappka
backend.

## Prerequisites

To run the backend the following programs are required:

* `docker` (19.03+)
* `docker-compoe` (1.27+)

## Downloading the repository

Prior to running the repository should be downloaded and all the
submodules need to be initialized. To do this please follow the
following commands:

```bash
git clone git@github.com:makimo/kajappka-dev.git
git submodule init
git submodule update
```

To download the updates to the backend code, do:

```bash
git pull
git submodule update
```

## Running the backend

To run the backend services, run the following command:

```bash
docker-compose up
```

> First run make take some time since all needed docker images will be
> downloaded and built.
