[![Published on webcomponents.org][webcomponents-image]][webcomponents-url]

# \<s-circle-progress\>

Polymer-based web component displaying a circular progress bar.

Inspired by element [\<progress-bubble\>](https://github.com/tehapo/progress-bubble).

## Demo

[Full demo][webcomponents-demo]

## Usage

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="s-circle-progress.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<s-circle-progress value="6" max="10">
  60%
</s-circle-progress>

<s-circle-progress value="30" angle="90" stroke-width="8">
  <b>30s</b>
</s-circle-progress>
```

### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--s-circle-progress-bg-stroke-color` | The background color of the circle | `--paper-grey-100`
`--s-circle-progress-stroke-color` | The stroke color of the circle | `--accent-color`
`--s-circle-progress-stroke-linecap` | The stroke-linecap svg attribute of the circle | `round`

## Installation

`bower i s-circle-progress -S`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## License

MIT: [StartPolymer/license](https://github.com/StartPolymer/license)

[webcomponents-image]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[webcomponents-url]: https://beta.webcomponents.org/element/StartPolymer/s-circle-progress
[webcomponents-demo]: https://beta.webcomponents.org/element/StartPolymer/s-circle-progress/demo/demo/index.html
