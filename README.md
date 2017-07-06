# JetBrains preset for Babel 6

This preset includes all plugins from the [official](https://babeljs.io/docs/plugins/#presets-official-presets) presets
`es2015-17`, `stage-2`, `react`,
and one extra plugin:
[`transform-strict-mode`](http://babeljs.io/docs/plugins/transform-strict-mode). `es2015` is used with `{modules: false}` option, because webpack 2 uses native imports for tree shaking.

**Note to maintainers**: to trigger publishing of the npm package append *\[Publish\]* to the commit message. For example:

*Tweaked the preset \[Publish\]* 

