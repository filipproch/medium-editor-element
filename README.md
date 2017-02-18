# \<medium-editor-element\>

Polymer element for https://github.com/yabwe/medium-editor

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
