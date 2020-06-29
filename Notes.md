# Notas

* Install browserify

```bash
npm install browserify --save-dev --save-exact
```

* Install watchify

```bash
npm install watchify --save-dev --save-exact
```

* Show browserify version

```bash
npx browserify --version
```

* Recursively bundle up all the required modules starting at main.js into a single file called bundle.js with browserify

```bash
npx browserify main.js -o public/js/bundle.js
```

* Watch all changes in main.js and all the required modules and generate bundle.js in each modification

```bash
npx watchify main.js -o public/js/bundle.js
```
