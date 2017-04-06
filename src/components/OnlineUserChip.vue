<template>
  <div class="online-user">
    <span class="mdl-chip mdl-chip--contact mdl-chip--deletable">
      <img class="mdl-chip__contact" :src="imgUrl"></img>
      <span class="mdl-chip__text">{{name}}</span>
    </span>
  </div>
</template>

<script>
export default {
  name: 'OnlineUserChip',
  props: ['name', 'imgUrl']
}
</script>
