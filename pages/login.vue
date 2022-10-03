<template>
<div>
  <h1>IM LOGIN PAGE</h1>
  <button @click="goToHome">GO TO HOME</button>
</div>
</template>

<script>
export default {
  methods:{
    goToHome(){
      this.$router.push("/")
    },
  }

}
</script>

<style>

</style>