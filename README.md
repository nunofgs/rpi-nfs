# NFSv3 for Raspberry Pi 2

This is a Dockerfile to set up [UNFS3](http://unfs3.sourceforge.net/).

# Usage

```shell
$ docker run \
  --privileged \
  -p 111:111 \
  -p 2049:2049
  -v /mnt/data:/data
  -v exports:/etc/exports
  nunofgs/rpi-nfs
```
