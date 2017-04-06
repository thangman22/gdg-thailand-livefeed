<template>
  <div class="demo-card-wide mdl-card mdl-shadow--2dp">
    <div class="mdl-card__title">
      <h5 class="mdl-card__title-text"><span class="contact-image-area"><img class="mdl-chip__contact" :src="imgUrl"></span></img> {{name}}</h5>
    </div>
    <div class="mdl-card__supporting-text">
      {{text}}
    </div>
  </div>
</template>

<script>
export default {
  name: 'MsgCard',
  props: ['imgUrl', 'name', 'text']
}
</script>
<style scoped>
  .demo-card-wide.mdl-card {
    width: 100%;
    min-height: 100px;
  }
  .mdl-card__title-text {
    font-size: 18px;
    color: #757575;
  }
  .mdl-chip__contact {
    height: 24px;
    width: 24px;
    vertical-align: middle;
  }
  .mdl-card__supporting-text{
    color: #212121;
  }
</style>
