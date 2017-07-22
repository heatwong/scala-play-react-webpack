# scala-play-react-webpack
Scala Play with React frontend and webpack

This is a starter project to fork from when developing new projects with a Scala Play backend and ReactJS + Jquery in the view layer.

# Setup
```
npm init
./node_modules/.bin/webpack --config webpack.config.js
sbt run
```

# Webpack
The webpack config makes Jquery available in all React code.
All bundled js files are compiled to app/assets/javascripts/build/
