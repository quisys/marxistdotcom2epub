# marxistdotcom2epub

A simple, POSIX-compliant shell script that converts ebooks from the marxist.com online reader to .epub files.

Simply copy the URL (ending in `/read`) and paste it after `marxistdotcom2epub`. Boom, epub!

**For a user-friendly graphical tool, check out [https://quisys.github.io/marxistdotcom2epub](https://quisys.github.io/marxistdotcom2epub)

## Dependencies

* `curl`
* `jq`
* `sh`
* `zip`

## Usage

```
git clone https://github.com/quisys/marxistdotcom2epub
cd marxistdotcom2epub
./marxistdotcom2epub [-v] [-o dir] url
```

## Installation

### System-wide

`sudo install -m 755 marxistdotcom2epub /usr/local/bin`

### User-only

```
mkdir -p ~/.local/bin
install -m 755 marxistdotcom2epub ~/.local/bin/
```

