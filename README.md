
# Create react app from scratch

```bash
# init
yarn init -y

# make directory
mkdir public src

# create index.html
touch public/index.html
vi public/index.html

# add libralies for build
yarn add -D webpack webpack-cli webpack-dev-server style-loader css-loader babel-loader copy-webpack-plugin
yarn add -D @babel/core @babel/preset-react @babel/preset-env

# add react libralies
yarn add react react-dom

# create gitignore
touch .gitignore
vi .gitignore

# create webpack.config.js
touch webpack.config.js
vi webpack.config.js

# crete frontend module
touch src/index.js src/App.js src/App.css
vi src/index.js
vi src/App.js
vi src/App.css

# create .babelrc
touch .babelrc
vi .babelrc

# edit package.json for starting server
vi package.json
```
