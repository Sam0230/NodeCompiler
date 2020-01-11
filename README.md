# NodeJSCompiler
A simple but useful NodeJS compiler.
### Installation
``` bash
sudo sh << END
mkdir -p /usr/local/bin
cp bin/nodejs-compiler /usr/local/bin/nodejs-compiler
chmod +x /usr/local/bin/nodejs-compiler
END
```
### Usage
```
  nodejs-compiler CODE
  Example: nodejs-compiler "$(cat example.js)" >example.compiled.js
```