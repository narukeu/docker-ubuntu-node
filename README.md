# Docker + Ubuntu + Node

业务需要一个基于 Ubuntu + Build Essential 的 Node.js 的镜像，留作自用。

## 包含

- curl
- build-essential
- ca-certificates
- gnupg
- Node.js (from NodeSource)

## 镜像地址

- [Docker Hub](https://hub.docker.com/repository/docker/narukeu/node-ubuntu)

- [GitHub](https://github.com/narukeu/docker-ubuntu-node)

## 镜像版本

| 标签                | Node 版本 | 基础                            | 备注           |
| ------------------- | --------- | ------------------------------- | -------------- |
| latest, 23-oracular | 23        | ubuntu:oracular（Ubuntu 24.10） | 仅作新版本测试 |
| 22                  | 22        | ubuntu:noble（Ubuntu 24.04）    | 常规镜像       |
| 22-jammy            | 22        | ubuntu:jammy（Ubuntu 22.04））  | 常规镜像       |
| 20                  | 20        | ubuntu:jammy（Ubuntu 22.04）    | 常规镜像       |

## 架构支持

镜像至少支持 `amd64` 架构，部分镜像还支持 `arm64` 架构。具体支持情况请参见 [Tag 页面](https://hub.docker.com/repository/docker/narukeu/node-ubuntu/tags)。

## 版权

入口文件 `docker-entrypoint.sh` 取自 Docker 官方镜像，遵循 MIT 许可协议。
