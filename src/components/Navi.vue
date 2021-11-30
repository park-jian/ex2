<template>
    <div class="nav">
      <router-link to="/golfClub">골프 클럽</router-link> |
      <router-link to="/podoHotel">포도호텔</router-link> |
      <router-link to="/theannexHotel">디아넥스호텔</router-link> |
      <router-link to="/biotopia">비오토피아</router-link> |
      <router-link to="/pLeisure">P-LEISURE</router-link> |
      <router-link to="/recruit">인재채용</router-link> |
      <router-link to="/board">Board</router-link>
       <router-view/>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.nav {
    height: 80px;
    line-height: 80px;
    background-color: pink;
}
</style>