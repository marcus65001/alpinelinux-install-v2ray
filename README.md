# alpinelinux-install-v2ray

## Dependency

### cURL

```
# apk add curl
```

## Download

```
$ curl -O https://raw.githubusercontent.com/marcus65001/alpinelinux-install-v2ray/master/install-release.sh
```

## Usage

```
# ash install-release.sh
```

## RC scripts

### Enable

```
# rc-update add v2ray
```

### Disable

```
# rc-update del v2ray
```

### Start

```
# rc-service v2ray start
```

### Stop

```
# rc-service v2ray stop
```

### Restart

```
# rc-service v2ray restart
```
