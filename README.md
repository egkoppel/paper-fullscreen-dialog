[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/egkoppel/paper-fullscreen-save-dialog)
[![Bower version](https://badge.fury.io/bo/paper-fullscreen-save-dialog.svg)](https://badge.fury.io/bo/paper-fullscreen-save-dialog)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# paper-fullscreen-save-dialog

Material design: [Full-screen dialogs](https://material.io/guidelines/components/dialogs.html#dialogs-full-screen-dialogs)

`paper-full-screen-dialog` is a full-screen dialog. When opened the dialog fills the whole screen.

Example:
<!---
```
<custom-element-demo height="150" width="300">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-fullscreen-dialog.html">
    <link rel="import" href="../paper-button/paper-button.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<!-- Call the open() function to open the dialog -->
<paper-button onClick="document.getElementById('dialog').open()">Open dialog</paper-button>
<paper-fullscreen-dialog id="dialog">
            <span class="title">Hello world</span>
            <p>Hello world</p>
</paper-fullscreen-dialog>
```
