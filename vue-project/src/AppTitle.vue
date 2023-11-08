<template>
  <div>
    <h1 class="mainTitle">{{ title }}</h1>
  </div>
</template>

<script>
export default {
  setup () {
    

    return {
      title: "La mia prima app con Vite!"
    }
  }
}
</script>

<style lang="css" scoped>
  .mainTitle{
    color: red;
    text-align: center;
    padding-top: 12px;
  }
</style>