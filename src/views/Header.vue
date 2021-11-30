<template>
  <div class="Header">
      <img src="@/assets/logo.png" width="40"> 
      <button>로그아웃</button>
      <button>정보수정</button>
      <Navi class="navi"></Navi>
   
  </div>
</template>

<script>
import Navi from '@/components/Navi.vue';

export default {
    components: {
        Navi
    }
}
</script>

<style scoped>

</style>