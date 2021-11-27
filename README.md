# vue HelloWorld

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```


### Publish to gitHubPages:
First of all: 

- change ghe publicPath in package.json for your folder in github Pages, 


Second:
```
npm run build
git add .
git commit -"version xxx"
git subtree push --prefix dist origin gh-pages
```

