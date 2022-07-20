<template>
  <div>
    <div>
      <input type="radio" id="html" value="HTML" v-model="favoriteLang" />
      <label for="html">HTML</label>
    </div>
    <div>
      <input type="radio" id="CSS" value="CS" v-model="favoriteLang" />
      <label for="CSS">CSS</label>
    </div>
    <div>
      <input type="radio" id="JS" value="JS" v-model="favoriteLang" />
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
      favoriteLang: ''
    //   체크박스는 배열로 바인딩했지만 라디오는 하나선택되는거라 문자열로해야함반드시
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
