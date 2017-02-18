# \<medium-editor-element\>

Polymer element for https://github.com/yabwe/medium-editor

## Usage

The following shows the usage of the element with it's properties

```html
<medium-editor
    id="myEditor"
    value="{{value}}">
</medium-editor>

<pre>[[value]]</pre>
```

by default, it should just work. It will output HTML using it's value property. If you want markdown output, just change the output property.

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
