# installing react through nvm and sass process

installing with nvm allows you to manage the versions

install node through : 
https://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/

install create-react-app through :
npm i create-react-app
# Note: if done through -g then uninstall using, npm unistall -g create-react-app

# How to use sass in react using create-react-app 2

check the package.json for 'react-scripts' this should be greater than 2.0.3

npm install node-sass

change the file from .css to .scss

in app.scss you can import the other scss files by @import './style/common.scss'
