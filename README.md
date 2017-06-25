# babel-preset-accelerator
Collection of Babel presets and plugins for all the development environments

## Installation

You'll install `babel-preset-accelerator`:

```
$ npm install babel-preset-accelerator --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `babel-preset-accelerator` globally.

## Usage

Add `accelerator` to the plugins section of your `.babelrc` configuration file. You can omit the `babel-preset-` prefix:

## For React without transform-runtime

```json
{
    "presets": [
        "accelerator"
    ]
}
```

## For with transform-runtime

```json
{
    "presets": [
        "accelerator/latest"
    ]
}
```

## For Nodejs

```json
{
    "presets": [
        "accelerator/node"
    ]
}
```

## For Webpack with React & transform-runtime & enabled the Tree shaking

```json
{
    "presets": [
        "accelerator/webpack"
    ]
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)





