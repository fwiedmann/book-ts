# Learning TypeScript

This project contains all the exercises I did for learning TypeScript based on the O'Reilly  TS book.

## How to setup TypeScript

First install NodeJS, which also comes with a package manager called `npm`. With NodeJS you can execute JavaScript code.

For Debian:

```bash
    curl -fsSL https://deb.nodesource.com/setup_15.x | sudo -E bash -
    sudo apt-get install -y nodejs  
```

Make sure you NodeJS was successfully installed

```bash
    node -v
```

Create a new npm configuration in your empty project folder

```bash
    npm --init
```

Install TSC and TSLint

```bash
    npm install --save-dev typescript tslint @types/node  
```

Init TS and TSLint

```bash
./node_modules/.bin/tsc --init  
./node_modules/.bin/tslint --init  
```
