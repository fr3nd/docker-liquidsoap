# liquidsoap docker image

## Description

Liquidsoap is a powerful and flexible language for describing your streams. It offers a rich collection of operators that you can combine at will, giving you more power than you need for creating or transforming streams

This image allows you to run liquidsoap in a completelly containerized
environment

## How to use this image

Run liquidsoap help:

```
docker run fr3nd/liquidsoap --help
```

## FAQ

### Why to containerize such a simple application?

In operating systems like RedHat/CentOS is not simple to install liquidsoap
without compiling and installing a lot of dependencies. Having it containerized
makes it much simpler to run.
