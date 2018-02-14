# DCinD

## Introduction

Docker Compose in Docker (dcind) with Git (and Make) installed

## Contents

- [Build](#build)
- [Push](#push)

## Build

```bash
docker build --force-rm --no-cache --compress -t rms1000watt/dcind-git:latest .
```

## Push

```bash
docker push rms1000watt/dcind-git:latest
```
