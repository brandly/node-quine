# node-quine

> A quine is a computer program which takes no input and produces a copy of its own source code as its only output.

[- wiki](https://en.wikipedia.org/wiki/Quine_(computing))

```shell
$ diff <(cat index.js) <(node index.js)
$ diff <(cat index.js) <(node index.js | node | node | node)
```
