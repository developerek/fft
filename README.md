[![LICENSE](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://github.com/nooncall/shazam/blob/master/LICENSE)
[![Build Status](https://github.com/nooncall/shazam/workflows/build/badge.svg)](https://github.com/nooncall/shazam/actions?query=workflow%3Abuild)
[![Go Report Card](https://goreportcard.com/badge/github.com/nooncall/shazam)](https://goreportcard.com/report/github.com/nooncall/shazam)
[![codecov](https://codecov.io/gh/nooncall/shazam/branch/master/graph/badge.svg)](https://codecov.io/gh/nooncall/shazam)

## Introduction

**shazam ([ʃə'zæm], Shazam) is a database middleware compatible with MySQL protocol, its predecessor is [Gaea](https://github.com/XiaoMi/Gaea).**

## function list

### basic function

- Multi-tenancy
- SQL transparent forwarding
- Annotate routing
- SQL Statistics (SQL Fingerprint, Slow SQL Log, etc.)
- Separation of reading and writing, load balancing from the library
- Custom SQL interception and filtering
- connection pool
- Configure hot loading
- IP/IP segment white list
- Global serial number

### Sub-library, sub-table function

- Sub-library: support mycat sub-library mode
- Table splitting: support kingshard table splitting
- Aggregation functions: support max, min, sum, count, group by, order by, etc.
- join: supports the join of fragmented tables and global tables, supports the join of multiple fragmented tables but with the same routing rules

## Install and use

- [Quickstart](docs/quickstart.md)
- [Configuration instructions](docs/configuration.md)
- [Basic concepts](docs/concepts.md)
- [SQL Compatibility](docs/compatibility.md)
- [FAQ](docs/faq.md)

## Design and implementation

- [Overall Architecture](docs/architecture.md)
- [Multi-tenant design and implementation](docs/multi-tenant.md)
- [Configuration Hot Reloading Design and Implementation](docs/config-reloading.md)
- [Design and implementation of backend connection pool](docs/connection-pool.md)
- [Design and implementation of prepare](docs/prepare.md)

## Community

### DingTalk
![Dingtalk](docs/assets/shazam_dingtalk.png)

### gitter
[![Gitter](https://badges.gitter.im/nooncall/shazam.svg)](https://gitter.im/nooncall/shazam)