<template>
  <div class="container p-5">
    <main class="border m-5 p-5">
      <router-view />
    </main>
  </div>
</template>

<script>
export default {

  data () {
    return {
      currentPage: ''
    }
  }

}
</script>

<style lang="scss">
@import "@/assets/stylesheets/all.scss";
.active {
  background-color: gray;
  color: #fff;
}
</style>
