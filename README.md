# mini.css Code Component
A [mini.css](https://minicss.org) module for better code presentation.

![Example](/readme_thumb.PNG)

## Installation

```
npm install mini.css-code-component

yarn add mini.css-code-component
```

## Usage

1. Create a `<pre>` element.
2. Wrap every line of code into a `<span class="code-line">`.
3. Apply highlights by wrapping text in `<span class="highlight-a">`, `<span class="highlight-b">` or `<span class="highlight-c">`.

#### Example
```html
<pre>
<span class="code-line"><span class="highlight-a">if</span> condition:</span>
<span class="code-line">  value = <span class="highlight-c">'Result:'</span> . <span class="highlight-b">10</span></span>
<span class="code-line">  <span class="highlight-a">print</span>(value)</span>
<span class="code-line"><span class="highlight-a">return</span></span>
</pre>
```

## Customization

You can customize the color palette and other parameters, by modifying and recompiling the [Sass file](https://github.com/Chalarangelo/mini.css-code-component/blob/master/src/components/code_component.scss).

## License

This **mini.css** module is licensed under the [MIT License](https://github.com/Chalarangelo/mini.css-code-component/blob/master/LICENSE).
