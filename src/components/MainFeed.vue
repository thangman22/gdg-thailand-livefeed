<template>
  <div class="main">
    <div class="mdl-grid title-area">
      <div class="mdl-cell mdl-cell--6-col mdl-cell--3-offset-desktop title mdl-cell--4-col-phone">ONLINE USER</div>
    </div>
    <div class="mdl-grid">
      <div class="mdl-cell mdl-cell--6-col mdl-cell--3-offset-desktop mdl-cell--4-col-phone"><OnlineUser></OnlineUser></div>
    </div>
    <div class="mdl-grid title-area">
      <div class="mdl-cell mdl-cell--6-col mdl-cell--3-offset-desktop title mdl-cell--4-col-phone">LASTEST POST</div>
    </div>
    <div class="mdl-grid">
      <div class="mdl-cell mdl-cell--6-col mdl-cell--3-offset-desktop mdl-cell--4-col-phone"><Stream></Stream></div>
    </div>
  </div>
</template>

<script>
import Stream from '@/components/Stream'
import OnlineUser from '@/components/OnlineUser'
export default {
  name: 'MainFeed',
  components: { OnlineUser, Stream }
}
</script>
<style scoped>
  .title{
    margin-top: 0;
    margin-bottom: 0;
  }
  .title-area{
    padding-bottom: 0;
    font-weight: 700;
    font-size: 0.8em;
    color: #757575;
  }
</style>
