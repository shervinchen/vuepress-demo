---
title: Tabs
---

## 效果

<ClientOnly>
    <tabs></tabs>
</ClientOnly>

## 源码

```html
<div class="tabs" data-active="2" data-disabled="3">
  <div class="tab-content">
    <div data-name="选项卡1" data-key="1" class="tab-panel">内容1</div>
    <div data-name="选项卡2" data-key="2" class="tab-panel">内容2</div>
    <div data-name="选项卡3" data-key="3" class="tab-panel">内容3</div>
    <div data-name="选项卡4" data-key="4" class="tab-panel">内容4</div>
  </div>
</div>
```

```javascript
new Tabs(document.querySelector(".tabs"), ($tab, index) => {
  console.log($tab, index);
});
```
