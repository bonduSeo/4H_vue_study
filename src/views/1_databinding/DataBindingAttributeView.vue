<template>
  <div>
    <input type="text" name="" id="" v-bind:value="userId" readonly />
    <!-- value라는 속성에 직접 데이터 바인딩함. 단방향 데이터 바인딩 -->
    <input type="text" name="" id="" :value="userId" readonly />
    <!-- 같은의미 -->
    <br />
    <img :src="imgSrc" alt="" style="width: 100px; height: auto" />
    <br />
    <input type="search" name="" id="" v-model="txt1" />
    <button :disabled="txt1 === ''">조회</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'bondu',
      imgSrc:
        'https://4.bp.blogspot.com/-o4RyOEhoHo8/WZVribxbufI/AAAAAAAABMk/0ZUqq5lpNp0H636rIbKgcVPE51gf51AaQCLcBGAs/s1600/adventure-time.png',
      txt1: ''
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
