# Install old version of LevelDB Homebrew package

Homebrew makes it somewhat difficult to install older version of packages. This repository contains a historic package install script, which can be used in tandem with `homebrew extract`.

This repository was forked and slightly adapted from: https://github.com/bagonyi/homebrew-formulae

## How to install LevelDB 1.22

```
brew tap graphbrain/homebrew-formulae git@github.com:graphbrain/homebrew-formulae.git
brew extract --version=1.22 leveldb graphbrain/formulae
brew install leveldb@1.22
```
