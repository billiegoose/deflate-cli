# deflate-cli
A CLI utility for compressing streams with `deflate` algorithm

## Install

```sh
npm i -g deflate-cli
```

(Note: the bin is named `deflate` not `deflate-cli`.)

## Use

You can either pipe the file (preferred) or specify the file name as a command line argument.

```sh
cat somefile | deflate
```

or

```sh
deflate somefile
```
