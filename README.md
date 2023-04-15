This repository is for learning purposes and refers to [teru01/toytcp](https://github.com/teru01/toytcp).

## setup

```sh
$ brew install --cask multipass
$ multipass launch lts --name toytcp
$ multipass mount ./ toytcp:/home/ubuntu/toytcp/
$ multipass shell toytcp
# and then run setup.sh and install rust
```
