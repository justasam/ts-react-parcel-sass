# ts-react-parcel-sass
Starter [TypeScript + React + Sass + Parcel]

## Getting started:
- Install Parceljs if you haven't already: `npm i -g parcel-bundler`
- Install dependencies: `npm i`
- Run: `parcel index.html`

## TSlint:
```
npm i -g tslint typescript
```

## Why no structure?
@dan_abramov:
> ...start by putting everything in one file; when it feels like it’s annoying, start splitting them up; when THAT gets annoying, maybe add some folders

Not convinced? Try something like this:
```
my-app
└── src
    └── components
        └── component-name
            ├── component-name.css
            ├── component-name.scss
            ├── component-name-container.js
            ├── component-name-redux.js
            ├── component-name-styles.js
            ├── component-name-view.js
            └── index.js
```
