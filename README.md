# Purescript Starter

git push -u origin master

## Installation

First install purescript and spago:

```
npm install -g purescript purescript-spago
```

Clone this repo, cd into it and run:

```
npm install && spago build
```

## Running

```
npm start
```
In another terminal:
```
npm server
```

## Compiling purescript code

__Instructions for VS Code__

Install both vscode-ide-purescript and PureScript Language Support extensions.

That will provide compilation on save to the output directory being watched by webpack.

Now you should be able to do changes in Main.purs and see them in the browser!

## TODO

- Purescript compilation output file watch
- Auto reload server on changes (maybe browsersync or - webpack-dev-server)
