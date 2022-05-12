mountbyname
===========

### Intro

I use Linux and I have a few extra devices that I'd like to mount/unmount by
their names. `udisksctl` allows me to mount/unmount devices, but it doesn't
allow doing it by name.

So I wrote a wrapper script in [Xonsh](https://xon.sh/) to do that.

### Usage

```
    mountbyname mount storage
    mountbyname unmount storage
```

The wrapper script also allows 'm' for mount and 'u' for unmount as the first
argument.

### Requirements

* udisksctl
* Xonsh
