## Boiler plate for react 

# Packages
* webpack - This packs all our source code and delivers it in the output directory
* webpack-cli - this is to enable us to run the webpack commands from command prompt
* webpack-dev-server - This is for starting an in memory server with hot reloading capabilities while we devlop
* babel-core - The core functionality of babel
* babel-loader - To be used with webpack to redirect some files to be processed by babel
* babel-preset-env - To transpile ES2016 to ES2015 for backward compatibility
* babel-preset-react - The babel component which deals with react
* react - React core functionality
* react-dom - For connecting react and DOM on browser. Only place used will be ReactDOM.render
* html-webpack-plugin - Web pack plugin which injects the output file into script tag of template html we provide it