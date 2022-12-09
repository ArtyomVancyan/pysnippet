<p align="center">
    <img alt="" src="https://user-images.githubusercontent.com/46633744/175888700-bd690caf-312b-4340-824e-cc3808ae3b80.svg">
    The plugin allows demonstrating Python snippets at StackOverflow.
</p>

<div align="center">

![][stackoverflow-tag] [![][snippet-js-size]][snippet-js-cdn] [![][snippet-min-js-size]][snippet-min-js-cdn] [![][license-tag]][license-url]

[stackoverflow-tag]: https://img.shields.io/badge/StackOverflow-plugin-blue?logo=stack-overflow&logoColor=white
[snippet-js-size]: https://img.badgesize.io/https:/raw.githubusercontent.com/pysnippet/pysnippet/latest/snippet.js?label=snippet.js
[snippet-min-js-size]: https://img.badgesize.io/https:/raw.githubusercontent.com/pysnippet/pysnippet/latest/snippet.min.js?label=snippet.min.js
[snippet-js-cdn]: https://cdn.jsdelivr.net/gh/pysnippet/pysnippet@latest/snippet.js
[snippet-min-js-cdn]: https://cdn.jsdelivr.net/gh/pysnippet/pysnippet@latest/snippet.min.js
[license-tag]: https://img.shields.io/badge/License-Apache_2.0-blue.svg
[license-url]: https://opensource.org/licenses/Apache-2.0
</div>

---

PySnippet is a JavaScript plugin that allows using Python snippets on StackOverflow, adding just one line of code. The plugin uses PyScript to run a python code in the browser. Using the PySnippet is effective if you want to show an output of simple things that primarily use neither OS nor drivers.

## ![](https://user-images.githubusercontent.com/44609997/206767057-f1080a93-cfec-4f43-bfb0-7ffe1dc135ec.svg) CDN

The sources have been published using the GitHub CDN of the <a href="https://www.jsdelivr.com/">jsdelivr</a>.
```text
https://cdn.jsdelivr.net/gh/pysnippet/pysnippet@latest/snippet.js
```
```text
https://cdn.jsdelivr.net/gh/pysnippet/pysnippet@latest/snippet.min.js
```

## ![](https://user-images.githubusercontent.com/44609997/206767090-c8f31371-3fc2-4920-a621-e44a05139733.svg) Usage

 1. Add the plugin as an external library in the `HTML` section.
    ```html
    <script src="https://cdn.jsdelivr.net/gh/pysnippet/pysnippet@latest/snippet.js"></script>
    ```
 2. Paste your Python code into the `JavaScript` section.
 3. Uncheck the "Show console" checkbox to hide the JavaScript console. The states of rest checkboxes do not matter and depend on your choice.
    - [ ] Show console
    - [ ] Use BabelJS / ES2015
    - [ ] Hide snippet by default
