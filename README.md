# glasss-cli

A CLI tool for the [glasss](https://github.com/lf32/glasss) Library

[![npm version](https://img.shields.io/npm/v/glasss-cli.svg?style=flat-square)](https://www.npmjs.org/package/glasss-cli)
[![install size](https://packagephobia.com/badge?p=glasss-cli)](https://packagephobia.com/result?p=glasss-cli)
[![npm downloads](https://img.shields.io/npm/dt/glasss-cli.svg?style=flat-square)](http://npm-stat.com/charts.html?package=glasss-cli)


## Installation

```
 npm i glasss-cli -g
 ```

## Help

```
 glasss --help
 ```

It will return this in the **command line**.

```
---------- glasss-cli ----------
A Command Line Interface for the glasss NPM package.
Usage: glasss [OPTION]... [DIRECTORY]...

Here are the list of ways for using the glasss-cli
  [OPTION]...                  [INFO]...
  init                       - This will create a glasss app in the current working directory.
  create-app [DIRECTORY]...  - This will create a glasss app(s) with the arguments as directory name .
  -h,      --help      display help and exit
  -v,      --version      display version and exit



glasss-cli v0.0.1
For more details visit https://npmjs.com/package/glasss-cli/
MIT License.
```

# Usage

* **For current working directory**

 ```
 glasss init
 ```

 It will return this message in the **command line**.

 ```
 Created a glass application in the current working directory.
 ```

* **For multiple directories**

 ```
 glasss create-app dir1 dir2 dir3
 ```

 It will return this message in the **command line**.

 ```
 :) created dir1 glasss application.
 :) created dir3 glasss application.
 :) created dir2 glasss application.
 ```

### API

- **[glasss](https://github.com/lf32/glasss)** - A glasssmorphism based NPM Library.

### License

MIT License.
