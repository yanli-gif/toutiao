<template>
  <div class="home">
      <van-button type="primary">主要按钮</van-button>
  </div>
</template>

<script>
import { Button } from 'vant';


export default {
  name: 'ContactList',
components:{
    [Button.name]:Button
}
  
}
</script>
