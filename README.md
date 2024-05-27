The cleanest barebones setup for React I found with ParcelJS.

```
npm install -g parcel-bundler
```

Just initialize vanilla JS project with:

```
npm init -y
```

Install react and react-dom:

```
npm install react react-dom
```

Install:

```
npm install --save-dev babel-preset-env babel-preset-react
```

and configure babel with `.babelrc`:

```
{
  "presets": ["env", "react"]
}
```

Finally add basic scaffolding with `index.html`, `index.js` and `App.js`.

Run with:

```
parcel index.html
```