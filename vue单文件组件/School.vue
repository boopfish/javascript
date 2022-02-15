<template>
  <div>
    <h1>{{ schoolName }}</h1>
    <h1>{{ schoolAddress }}</h1>
  </div>

</template>

<script>
export default {
  name: "School",
  data() {
    return {
      schoolName: "学校名称",
      schoolAddress: "重庆渝中"
    }
  }
}
</script>

<style scoped>

</style>