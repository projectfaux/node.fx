Faux is currently reliant on Node.js and Git enviroments, so to get started just do the following.

# requirements

First install the required software, or ensure your copy meets the minimum requirements.

* _minimum:_

  * Node.js v4 - [https://nodejs.org/en/blog/release/v4.0.0/](https://nodejs.org/en/blog/release/v4.0.0/)
  * Git v2 - [https://github.com/git/git/blob/master/Documentation/RelNotes/2.0.0.txt](https://github.com/git/git/blob/master/Documentation/RelNotes/2.0.0.txt)

* _recomended:_

  * Node.js v7.6 [https://nodejs.org/en/blog/release/v7.6.0/](https://nodejs.org/en/blog/release/v7.6.0/)
  * Git v2.12 - [https://github.com/git/git/blob/master/Documentation/RelNotes/2.12.0.txt](https://github.com/git/git/blob/master/Documentation/RelNotes/2.12.0.txt)

# install

Depending on how you intend to use Faux, you can install _node.fx_, the Node.js based SDK for Faux, via NPM:

## command line

To use _node.fx_ as a command line tool:

```shell
npm install -g node.fx
```

## node module

To use _node.fx_ as a Node.js module:

```shell
npm install --save node.fx
```

You can also simple use it as a development module:

```shell
npm install --save-dev node.fx
```

# development

Want to contribute (fix a bug, add a feature, etc), using Git:

```shell
git clone https://github.com/projectfaux/node.fx.git
cd node.fx
npm run setup
```
