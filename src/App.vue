<template>
<!-- Always shows a header, even in smaller screens. -->
<div class="mdl-layout mdl-js-layout mdl-layout--fixed-header">
  <header class="mdl-layout__header">
    <div class="mdl-layout__header-row">
      <!-- Title -->
      <span class="mdl-layout-title">Google I/O Extend 2017 Live Feed</span>
      <div class="mdl-layout-spacer"></div>
    </div>
  </header>
  <main class="mdl-layout__content">
    <div class="page-content"><router-view></router-view></div>
  </main>
</div>
    
</template>

<script>
export default {
  name: 'app'
}
</script>
