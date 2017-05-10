[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/egkoppel/paper-fullscreen-save-dialog)
[![Bower version](https://badge.fury.io/bo/paper-fullscreen-save-dialog.svg)](https://badge.fury.io/bo/paper-fullscreen-save-dialog)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# paper-fullscreen-save-dialog
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-fullscreen-save-dialog.html">
    <link rel="import" href="../paper-button/paper-button.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-button onClick="document.getElememtById('dialog').open()">Hi</paper-button>
<paper-fullscreen-save-dialog id="dialog">
          <paper-fullscreen-save-dialog id="dialog" confirm-button="Done">
            <span class="title">Hello world</span>
            <p>Hello world</p>
        </paper-fullscreen-save-dialog>
</paper-fullscreen-save-dialog>
```
A polymer fullscreen paper dialog, with both save and cancel buttons
