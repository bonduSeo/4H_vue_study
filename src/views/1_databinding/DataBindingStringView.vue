<template>
  <div>
    <h1>Hello {{ userName }}</h1>
    <p>{{ message }}</p>
    <!-- 단방향 바인딩 -->
  </div>
</template>
<script>
export default {
  data() {
    return {
      userName: 'John Doe',
      message: 'welcome haah',
      arr: [],
      obj: {}
    }
  }
}
</script>
<style scoped></style>
