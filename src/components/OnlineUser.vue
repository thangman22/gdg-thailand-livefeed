<template>
  <div class="online-user">
    <OnlineUserChip imgUrl="/templates/dashboard/images/user.jpg" name="Deletable Contact Chip"></OnlineUserChip>
  </div>
</template>

<script>
import OnlineUserChip from '@/components/OnlineUserChip'
export default {
  name: 'OnlineUser',
  components: { OnlineUserChip }
}
</script>
