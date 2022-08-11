## Install
```
xxh +I xxh-shell-nushell+git+https://github.com/agnosticlines/xxh-shell-nushell
```
Connect:
```
xxh myhost +s nushell
```
To avoid adding `+s` every time use xxh config in `~/.config/xxh/config.xxhc` (`$XDG_CONFIG_HOME`):
```
hosts:
  ".*":                     # Regex for all hosts
    +s: nushell
```

## Plugins
In theory these can exist, but I haven't figured out a smooth way to make them work with elvish yet. Possible a wrapper script that loads multiple scripts in sequence, who knows. Some day :)

## Thanks
The [the xxh shell example](https://github.com/xxh/xxh-shell-example) for showing me where to start.
The [elvish shell](https://github.com/krageon/xxh-shell-elvish) which I shamelessly ripped to make this
