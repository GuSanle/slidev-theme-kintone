<template>
  <div class="slidev-layout kintone-layout">
    <div class="kintone-header">
      <div class="title">
        <slot name="title"></slot>
      </div>
    </div>
    <div class="content">
      <slot name="content"></slot>
    </div>
    <div class="bottom">
      <slot name="bottom"></slot>
    </div>
    <div class="kintone-footer"></div>
    <div class="kintone-logo"></div>
  </div>
</template>

<style scoped>
.title {
  font-size: 2em;
  font-weight: bold;
  margin: 2em;
}

.content {
  margin: 2em;
}

.bottom {
  margin: 2em;
}
</style>