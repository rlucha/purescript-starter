# Purescript Starter

git push -u origin master

## Installation

First install purescript and spago:

```
npm install -g purescript purescript-spago
```

Clone this repo, cd into it and run:

```
npm install
```

## Running (WIP)

Open three terminals (yes, I know)

Terminal 1
```
npm run js
```

Terminal 2 (won't reload on changes, TODO)
```
spago build
```

Terminal 3
```
$ Any webserver pointing to src/index.html
```

Now you should be able to do changes and see them in the browser!

## TODO

- Purescript compilation output file watch
- Auto reload server on changes (maybe browsersync or - webpack-dev-server)
