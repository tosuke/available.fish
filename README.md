# available.fish
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)


Check if the command is available

## :mag: Usage
```fish
if available fzf
  # if 'fzf' command is available
else
  # if not
end
```

## :package: Installation
### Using [Fisherman](https://github.com/fisherman/fisherman)
```sh
$ fisher Tosuke/available.fish
```


### Using [Fundle](https://github.com/tuvistavie/fundle)
Add

```fish
fundle plugin 'Tosuke/available.fish'
```

to your `config.fish`, reload your shell and run `fundle install`


### Using [Fresco](https://github.com/masa0x80/fresco)
```sh
$ fresco Tosuke/available.fish
```


### Manually
```sh
$ curl https://raw.githubusercontent.com/Tosuke/available.fish/master/functions/available.fish > $HOME/.config/fish/functions/available.fish
```

