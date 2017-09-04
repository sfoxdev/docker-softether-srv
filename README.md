# Softether VPN Server

SoftEther VPN ("SoftEther" means "Software Ethernet") is one of the world's most powerful and easy-to-use multi-protocol VPN software. It runs on Windows, Linux, Mac, FreeBSD and Solaris.

[![Docker Build Status](https://img.shields.io/docker/build/sfoxdev/softether-srv.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/automated/sfoxdev/softether-srv.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/pulls/sfoxdev/softether-srv.svg?style=flat-square)]()
[![Docker Build Status](https://img.shields.io/docker/stars/sfoxdev/softether-srv.svg?style=flat-square)]()

## Usage

### Run container

```
docker run -d --cap-add NET_ADMIN -p 443:443/tcp -p 992:992/tcp -p 1194:1194/udp -p 5555:5555/tcp --name vpn-srv sfoxdev/softether-srv
```
