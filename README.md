# \<medium-editor-element\>

Polymer element for https://github.com/yabwe/medium-editor

## Demo

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="medium-editor-element.html">
    <style>
      #myEditor {
      	width: 100%;
        min-height: 300px;
        border-bottom: 1px solid #2a2a2a;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<template is="dom-bind">
  <medium-editor
      id="myEditor"
      value="{{value}}">
  </medium-editor>

  <pre>[[value]]</pre>
</template>
```

## Usage

__Basic example, HTML output__

```html
<medium-editor
    id="myEditor"
    value="{{value}}">
</medium-editor>

<pre>[[value]]</pre>
```

__Markdown output__

```html
<medium-editor
    id="myEditor"
    output="markdown"
    value="{{value}}">
</medium-editor>

<pre>[[value]]</pre>
```

## Development

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### View element locally

```
$ polymer serve
```

### Running Tests

```
$ polymer test
```
