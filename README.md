# oslab-env 

[![Build Docker Image](https://github.com/PAN-Ziyue/oslab-env/actions/workflows/build.yaml/badge.svg)](https://github.com/PAN-Ziyue/oslab-env/actions/workflows/build.yaml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/PAN-Ziyue/oslab-env/blob/main/LICENSE) [![Docker Pulls](https://img.shields.io/docker/pulls/alphavake/oslab)](https://hub.docker.com/r/alphavake/oslab) [![Docker Image Size](https://img.shields.io/docker/image-size/alphavake/oslab/latest)](https://hub.docker.com/r/alphavake/oslab)

**oslab** is a toolchain image for operating system course in ZJU.

## Usage

```bash
$ docker pull alphavake/oslab
```

The default width is set to 64-bit. If you need a 32-bit toolchain:

```bash
$ docker pull alphavake/oslab:rv32
```

## Toolchain List

- **qemu-system-riscv64**: v7.1.0
- **riscv-gnu-toolchain**: master

## LICENSE

ZiYue PAN @ [MIT](https://github.com/PAN-Ziyue/oslab-env/blob/main/LICENSE)
