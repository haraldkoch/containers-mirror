# Container Images Mirror

Stop-gap container registry mirror of upstream applications that only use Docker Hub

## Purpose

This is to get around Docker Hub rate-limiting (100 pulls / 6 hours, or authenticated 200 pulls / 6 hours). It is considered a stop-gap until the maintainers of the applications below support a different Container Registry.

## Supported images

When upstream maintainers add support for an additional registry, the images here will be purged after awhile.

| Name                                                                                                      | Upstream Issue                                                                                                                                                                                   |
|-----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [1password/*](https://github.com/1Password/connect)                                                       | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/1Password/connect/56)](https://github.com/1Password/connect/issues/56)                                                 |
| [excalidraw/excalidraw](https://github.com/excalidraw/excalidraw)                                         | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/excalidraw/excalidraw/6143)](https://github.com/excalidraw/excalidraw/issues/6143)                                 |

## Docker OSS Program

Certain containers may not be rate limited if they are in Docker Hub's OSS Program or verified publishers. Below is a list of applications I have discovered to be part of these program.

- bitnami/*
- grafana/*
- intel/intel-deviceplugin-operator
- intel/intel-gpu-plugin
- nodered/node-red
- rook/ceph
