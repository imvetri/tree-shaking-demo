# Demo: tree-shaking

This project demonstrates how to do tree-shaking (removal of unused exports) with webpack 2 and Babel 6.

Installation:

```
cd tree-shaking-demo/
npm install
```

There are three ways in which you can build and run the web app:

* Build once:
    * `npm run build`
    * Open `build/index.html`
* Watch files continuously, rebuild incrementally, whenever one of them changes:
    * `npm run watch`
    * Open `build/index.html`, manually reload page in browser whenever there was a change
* Hot reloading via webpack dev server:
    * `npm start`
    * Go to `http://localhost:8080/`, page reloads automatically when there are changes
