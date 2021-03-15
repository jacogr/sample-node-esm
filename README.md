# sample-node-esm

Sample with ESM sources. There is a `"type": "module"` specifier in `package.json`, so it defaults to ESM.

Tested with -

```
$ node --version
v14.15.1
```

Default operation (import syntax) -

```
$ node ./index.js
0x126263fa5c7259a364c9762c50494fb285e4a78de7ec2a9e528385e8e29f0a47
```

And to execute the CJS version, overriding default `type` specifier in `package.json`.

```
$ node ./index.cjs
0xe39df9a0e1b79b66770108c7c62239d7d76b61b7fdfe10798441c72099336b56
```
