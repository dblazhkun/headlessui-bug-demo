## This repo demonstrates unexpected scroll after when closing the modal.
### Steps to reproduce:
1. run dev server and open the localhost page in Safari browsers
2. click the `Open dialog` button
3. close dialog by clicking on backdrop or pressing escape

In order to enable a workaround for this behaviour, uncomment following line of code in template section of `App.vue`:
``` 
<!--<button v-if="!visible" class="absolute transparent" />-->
```
---
### For start dev server run following commands
```
npm i
```
```
npm run dev
```
