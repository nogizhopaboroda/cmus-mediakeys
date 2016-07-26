# cmus-mediakeys
Control cmus player via global mediakeys

Available keys: **play, prev, next**

## installation
```shell
$ git clone https://github.com/nogizhopaboroda/cmus-mediakeys.git
$ cd cmus-mediakeys
$ npm install
$ # run mediakeys handler
$ ./mediakeys
```

## known issues

On Mac OS X, node v4 `npm install` fails when installs "mediakeys" module.

Issues described [here](https://github.com/nogizhopaboroda/cmus-mediakeys/issues/1) and [here]( https://github.com/tcr/mediakeys/issues/3)

Known workarounds:

- downgrading node to version 0.10
- updating XCode to version >=7


If you like this project, check out also cmus plugin manager [cmus-bundler](https://github.com/nogizhopaboroda/cmus-bundler)
