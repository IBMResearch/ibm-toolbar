[![Build status][travis-image]][travis-url]

## \<ibm-toolbar\>

A horizontal toolbar containing items that can be used for label, navigation,
search and actions.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="ibm-toolbar.html">
    <link rel="import" href="ibm-toolbar-logo.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<ibm-toolbar>
  <a href="#" title="Go home">
    <ibm-toolbar-logo></ibm-toolbar-logo>
  </a>
  <span main-title spacer>App name</span>
</ibm-toolbar>
```

[travis-image]: https://travis-ci.org/IBMResearch/ibm-toolbar.svg?branch=master
[travis-url]: https://travis-ci.org/IBMResearch/ibm-toolbar
