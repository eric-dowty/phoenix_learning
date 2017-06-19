# Documentation for Phoenix learning

## React
#### Setup
1. Initialize the app
   ```
   npm init
   ```
1. Configure webpack to run node server (package.json), add to scripts
   ```
   "start": "node server.js",
   ```
1. Add Babel as dev dependency
   ```
   sudo npm install --save-dev babel-core babel-loader babel-preset-es2015 babel-preset-react babel-preset-stage-0
   ```
1. Add Babel presets to webpack
   ```
   "babel": {
     "presets": ["es2015", "react", "stage-0"]
   }
   ```
1. Add webpack and webpack dev server as dependencies
   ```
   sudo npm install --save-dev webpack@1.x webpack-dev-server@1.x prr
   ```
1. Add React as webpack dependency
   ```
   sudo npm install --save react react-dom
   ```
1. Create webpack config file (check commit for contents)
   ```
   touch webpack.config.js
   ```
1. Create server.js file (check commit for contents)
   ```
   touch server.js
   ```
1. Create index.html file (check commit for contents)
   ```
   touch index.html
   ```
1. Create index.js file (check commit for contents)
   ```
   mkdir app
   touch app/index.js
   ```


## Phoenix
#### Setup
1. Initialize the app
   ```  
   mix phoenix.new phoenix-chat-api --app phoenix_chat --module PhoenixChat --no-brunch
   ```
