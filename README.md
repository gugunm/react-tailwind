## Install Prod Dependencies

`yarn add react react-dom react-router-dom easy-peasy`

## Install Dev Dependencies

`yarn add --dev babel-cli@6.24.1 babel-core@6.25.0 babel-loader@7.1.1 babel-plugin-transform-class-properties@6.24.1 babel-plugin-transform-object-rest-spread@6.23.0 babel-polyfill@6.26.0 babel-preset-env@1.5.2 babel-preset-react@6.24.1 webpack@3.1.0 webpack-dev-server@2.5.1 sass-loader@6.0.6 style-loader@0.18.2 validator@8.0.0 node-sass normalize.css@7.0.0 css-loader@0.28.4 extract-text-webpack-plugin@3.0.0`

`yarn add --dev babel-preset-es2015 babel-preset-stage-2`

`yarn global add webpack-cli`

## Install Tailwind

[Reference](https://blog.logrocket.com/webpack-from-scratch-for-tailwind-css-with-react/)

`yarn add --dev tailwindcss autoprefixer postcss-loader postcss-import mini-css-extract-plugin(postcss-cli )` <br>
Next, we generate a Tailwind config file. In your terminal type: <br>
npx tailwindcss init <br>
create a file called `postcss.config.js` and add this code:
