### Create React App without create-react-app

### Setup project 
- create package.json
```
npm init -y
```

- install react
```
npm install react react-dom
```

- install babel with webpack
```
npm install --save-dev @babel/core babel-loader @babel/preset-env @babel/preset-react 
```

- create file `.babelrc` and copy code below
```
{  
 "presets": [
        "@babel/preset-react",
        "@babel/preset-env"
            ]
}
```

- install webpack tool
```
npm install --save-dev webpack webpack-cli webpack-dev-server
```

- install loaders
```
npm install --save-dev html-webpack-plugin style-loader css-loader file-loader
```

- create file `webpack.config.js`

- add need files

- add scripts below to package.json
```
"script" {
  "start": "webpack serve  --hot --open",
  "build": "webpack --config webpack.config.js --mode production"
}
```

#### Read more is [here](https://dev.to/riddhiagrawal001/create-react-app-without-create-react-app-2lgd) or [here](https://fullstack.edu.vn/blog/phan-1-tao-du-an-reactjs-voi-webpack-va-babel.html)