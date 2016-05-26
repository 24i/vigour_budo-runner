# budo-runner

<!-- VDOC.badges standard; npm; coveralls -->
<!-- DON'T EDIT THIS SECTION (including comments), INSTEAD RE-RUN `vdoc` TO UPDATE -->
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![npm version](https://badge.fury.io/js/budo-runner.svg)](https://badge.fury.io/js/budo-runner)
<!-- VDOC END -->

## Getting started
To get started install `budo-runner` from npm:

```shell
npm i budo-runner --save-dev
```

or globally

```shell
npm i budo-runner -g
```

#### Usage
You can run it by following

```shell
budo-runner example/something(.js)
```

-

Also, you can put it to your scripts in `package.json`.

So it can look like this:

```json
"scripts": {
  "dev": "budo-runner"
}
```

and run examples by typing:

```shell
npm run dev example/something(.js)
```
