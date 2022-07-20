<template>
  <div>
    <div>
      <input type="checkbox" id="html" value="HTML" v-model="favoriteLang" />
      <!-- 이럴때만 아이디를 쓴다 -->
      <!-- 체크박스는 checked라는 속성이 양방향 데이터바인딩됨 value가 아니고 -->
      <label for="html">HTML</label>
    </div>
    <div>
      <input type="checkbox" id="CSS" value="CS" v-model="favoriteLang" />
      <label for="CSS">CSS</label>
    </div>
    <div>
      <input type="checkbox" id="JS" value="JS" v-model="favoriteLang" />
      <label for="JS">JS</label>
    </div>
    <div>선택한지역: {{ favoriteLang }}</div>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      favoriteLang: ['JS']
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
