# NodeCompiler
A simple but useful NodeJS compiler.
### Installation
``` bash
sudo sh << END
mkdir -p /usr/local/bin
cp node-compiler /usr/local/bin/node-compiler
chmod +x /usr/local/bin/node-compiler
END
```
### Usage
```
  node-compiler CODE
  Example: node-compiler "$(cat example.js)" >example.compiled.js
```