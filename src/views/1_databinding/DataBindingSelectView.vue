<template>
  <div>
    <select v-model="selectedCity">
        <!-- v-model 양방향 데이터바인딩.. 아무데나 쓸수있는게 아니고 이렇게 사용자가 값을 변경할수있는거에만 쓸수있음 -->
      <option value="00"></option>
      <option value="02">서울</option>
      <option value="051">부산</option>
      <option value="064">제주</option>
    </select>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      selectedCity: '051'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
