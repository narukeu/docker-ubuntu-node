# Docker + Ubuntu + Node

业务需要一个基于 Ubuntu + Build Essential 的 Node.js 的镜像，留作自用。

Docker Hub 地址：https://hub.docker.com/repository/docker/narukeu/node-ubuntu

## 镜像版本

| 标签                | Node 版本 | 基础                            | 备注                                |
| ------------------- | --------- | ------------------------------- | ----------------------------------- |
| latest、23-oracular | 23        | ubuntu:oracular（Ubuntu 24.10） | 仅作新版本测试，，amd64、arm64 可用 |
| 22                  | 22        | ubuntu:noble（Ubuntu 24.04）    | 常规镜像，amd64、arm64 可用         |
| 22-jammy            | 22        | ubuntu:jammy（Ubuntu 22.04））  | 常规镜像                            |
| 20                  | 20        | ubuntu:jammy（Ubuntu 22.04）    | 常规镜像                            |
