## &lt;ibm-toolbar&gt;

`<ibm-toolbar>` is a horizontal toolbar containing items that can be used for label, navigation, search and actions.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="ibm-toolbar.html">
    <link rel="import" href="ibm-toolbar-logo.html">
    <div class="grey-background">
      <next-code-block></next-code-block>
    </div>
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
