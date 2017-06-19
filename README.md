# Documentation for Phoenix learning

## React
#### Setup
1. Initialize the app
   ```
   npm init
   ```
2. Configure webpack to run node server (package.json), add to scripts
   ```
   "start": "node server.js", 
   ```
3. Add Babel as dev dependency
   ```
   sudo npm install --save-dev babel-core babel-loader babel-preset-es2015 babel-preset-react babel-preset-stage-0
   ```
4. Add Babel presets to webpack
   ```
   "babel": {
     "presets": ["es2015", "react", "stage-0"]
   }
   ```
5. Add webpack and webpack dev server as dependencies
   ```
   sudo npm install --save-dev webpack@1.x webpack-dev-server@1.x prr
   ```
6. Add React as webpack dependency
   ```
   sudo npm install --save react react-dom
   ```



## Phoenix
#### Setup
1. Initialize the app
   ```  
   mix phoenix.new phoenix-chat-api --app phoenix_chat --module PhoenixChat --no-brunch
   ```
