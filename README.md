# Elm language custom image
Dev environment for http://elm-lang.org/

## Details
This is an image containing the build of Elm compiler's [0.19.1](https://github.com/elm/compiler/tree/0.19.1/) version.\
It also contains npm and node to make the REPL work.

## How to use
Host:
```bash
docker container run -it --rm kraftdorian/elm:0.19.1-alpine3.16 /bin/ash
```

Container:
```bash
elm
```
