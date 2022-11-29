## Setup webpack 5 with devDependecies:

- "@babel/core": "^7.20.5",
- "@babel/preset-env": "^7.20.2",
- "babel-loader": "^9.1.0",
- "css-loader": "^6.7.2",
- "html-webpack-plugin": "^5.5.0",
- "sass": "^1.56.1",
- "sass-loader": "^13.2.0",
- "style-loader": "^3.3.1",
- "webpack": "^5.75.0",
- "webpack-cli": "^5.0.0",
- "webpack-dev-server": "^4.11.1"

## Clone

- to clone repository you have to go to folder where you want to create your app
- open your code editor
- open terminal and type:
```bash
git clone https://github.com/rafal19987/setup.git
cd setup
```

## Install

- when you are in your local folder with cloned setup by prev step, type into terminal
```bash 
npm i
```

## Build App

```bash
npm run build
```

## Run App

```bash
npm run dev
```

# Change title of your webpage
- open webpack.config.js by using your code editor
- scroll to bottom and change title value in plugins
 ```js
  plugins: [
    new HtmlWebpackPlugin({
      title: 'Webpack App', // right here you can change your title to display
      filename: 'index.html',
      template: 'src/template.html',
    }),
  ],
 ```
