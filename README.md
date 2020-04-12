# elm-rte-package-example

This is an example of importing the elm-rte-toolkit into a project.

Prerequisites:

```bash
npm install --save-dev @webcomponents/webcomponentsjs
npm install --save-dev elm-rte-toolkit
elm install mweiss/elm-rte-toolkit
```

In `index.js`, we import in the following order

```js
import '@webcomponents/webcomponentsjs/webcomponents-bundle.js'
import '@webcomponents/webcomponentsjs/custom-elements-es5-adapter.js'
import 'elm-rte-toolkit';
// ... Elm initialization
```


To run in development use `elm-app start`.  To build, use `elm-app build`.  For more information about `elm-app`, see the [create-elm-app repo](https://github.com/halfzebra/create-elm-app) 