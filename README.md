# Hy Elements

Hy Elements is a small collection of web components I've built in the process of building [Hydejack](https://hydejack.com/).  


## [hy-drawer](https://www.webcomponents.org/element/hy-drawer)

<!--
```
<custom-element-demo height="250">
  <template>
    <script src="https://unpkg.com/@webcomponents/webcomponentsjs@1.1.0"></script>
    <link rel="import" href="https://unpkg.com/hy-drawer/dist/webcomponent/hy-drawer.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hy-drawer id="drawer" align="left" touch-events mouse-events>
  <p>Arbitrary content here.</p>
</hy-drawer>

<a onclick="window.drawer.toggle()">☰</a>
```

## [hy-push-state](https://www.webcomponents.org/element/hy-push-state)

<!--
```
<custom-element-demo>
  <template>
    <script src="https://unpkg.com/@webcomponents/webcomponentsjs@1.1.0"></script>
    <link rel="import" href="https://unpkg.com/hy-push-state/dist/webcomponent/hy-push-state.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hy-push-state initial-href="https://qwtel.com/hy-push-state/example/simple/" prefetch>
  <p>
    <a href="./1.html">Page 1</a>
    <a href="./2.html">Page 2</a>
    <a href="./3.html">Page 3</a>
  </p>
  <p>Super simple example.</p>
</hy-push-state>
```