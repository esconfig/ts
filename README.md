# @esconfig/ts

Universal tsconfig settings.

## Install

```sh
npm i @esconfig/ts -D
```

## Usage

Add to your `tsconfig.json`:

The base configuration:

```js
"extends": "@esconfig/ts/base.json"
```

Configuration for Node project:

```js
"extends": "@esconfig/ts/node.json"
```

Configuration for Browser project:

```js
"extends": "@esconfig/ts/vanilla.json"
```

Configuration for Vue project:

```js
// Vue2
"extends": "@esconfig/ts/vue2.json"

// Vue3
"extends": "@esconfig/ts/vue3.json"
```
