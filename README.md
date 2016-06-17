# Express Webpack Boilerplate
   * ES6 to transform ES5
   * Include CSS
   * Server EXPRESS (port:3000)
   * Structure folders:
```json
   {
       "dist": "Distribution for files",
       "src": "Source files",
       "static": "Files that are not compiled",
       "config": "configuration files for example: webpack.config.js, serverExpress.js"
   }
```
   * Branch:
```json
   {
       "html": "jade",
       "master": ["stylus", "sass", "jade"],
       "none": "not including loaders",
       "style": ["stylus", "sass"],
   }
```

## Installation

```bash
git clone https://github.com/Gersom/express-webpack-boilerplate.git
cd express-webpack-boilerplate
npm install
npm run dev # compiled files
npm run watch # compiled watch files
```

## License
express-webpack-boilerplate is licensed under [The MIT License](LICENSE).
