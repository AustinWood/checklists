# React checklist

## Git

`touch .gitignore`
https://github.com/appacademy/dotfiles/blob/master/dot/gitignore
`TODO: fork and edit linked repo`

## Setup directory tree:

```
index.html
frontend/
  actions/
  components/
  reducers/
  store/
  util/
  entry.jsx
```

With one line in the command line: `touch index.html; mkdir frontend; cd frontend; touch entry.jsx; mkdir actions components reducers store util`

## NPM

```
npm init -y
npm install --save webpack react react-dom babel-core babel-loader babel-preset-es2015 babel-preset-react redux react-redux lodash webpack-dev-server
```
Add `react-router` to the list, if needed.

## Webpack

`touch webpack.config.js`
