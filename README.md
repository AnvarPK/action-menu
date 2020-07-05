## Usage

[Check the result](https://action-menu.vercel.app)

- To Run locally.
- Install packages:
  - `npm install` or `yarn install`.
- `npm run start:dev`: Run `webpack-dev-server` at `localhost:9000`. Includes live reloading on any Javascript/SCSS/HTML changes.
- `npm run start`: Builds files and runs a local production server on `localhost:8080` with `http-server`.
- `npm run build`: Build files to the `dist` folder. Transpiles down to ES5 and bundles all JS into `app.bundle.js`. Transpiles SCSS to CSS and adds prefixing into `style.bundle.css`. Copies static assets and HTML over, and bundled CSS and JS gets added to HTML file.

## Code

[Download source code](https://github.com/AnvarPK/action-menu/archive/master.zip)

- [HTML](https://github.com/AnvarPK/action-menu/blob/master/src/index.html)
- [SCSS](https://github.com/AnvarPK/action-menu/tree/master/src/style)

## Tools used

- [Webpack static HTML boilerplate](https://github.com/erickzhao/static-html-webpack-boilerplate.git)
- [Hosting](https://vercel.com)
