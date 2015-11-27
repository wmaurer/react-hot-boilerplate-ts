>## Deprecation Notice

>This boilerplate is based on [react-hot-loader](https://github.com/gaearon/react-hot-loader) which is deprecated. A new boilerplate which uses React Transform, can be found [here](https://github.com/wmaurer/react-transform-boilerplate-ts).

react-hot-boilerplate-ts
========================

An (almost) minimal dev environment to enable live-editing Typescript/ReactJS components.

This a copy of Dan Abramov's react-hot-boilerplate (https://github.com/gaearon/react-hot-boilerplate), but uses ts-loader/Typescript instead of babel-loader/Babel.

### Usage

```
npm install
npm start
open http://localhost:3000
```

### Extras

To show the advantages of Typescript, the typings for React have been included.

The `App` component has a `name` property which has been defined on the interface (`IAppProps`) for `props`, i.e. the first generic parameter to `Component`.

If you were to remove the name property when using the component (in `index.tsx`), then you'll receive a typescript compile error.

If you're using a suitably advanced editor or editor plugin, you'll also get intellisense and edit-time error messages. This works with the [atom](http://atom.io) editor and the atom [atom-typescript](https://atom.io/packages/atom-typescript) plugin.

### TODO

tslint

### Dependencies

* React
* Webpack
* [webpack-dev-server](https://github.com/webpack/webpack-dev-server)
* [typescript](https://github.com/Microsoft/TypeScript)
* [ts-loader](https://github.com/TypeStrong/ts-loader)
* [react-hot-loader](https://github.com/gaearon/react-hot-loader)

### Resources

* [react-hot-boilerplate on Github](https://github.com/gaearon/react-hot-boilerplate)
* Ping [waynemaurer](https://twitter.com/waynemaurer) on Twitter
