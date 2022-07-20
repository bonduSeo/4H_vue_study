<template>
  <div>
    <input type="text" v-model="userId" @change="myFunction" />
    <!-- v-model은 양방향 데이터바인딩. 대단한거임. 바닐라자바스크립트보다 코드를 엄청줄일수있음 -->
    <button @click="myFunction">클릭</button>
    <button @click="changeData">변경</button>
    <br />
    <input type="text" v-model="num1" /> +
    <input type="text" v-model="num2" /> =
    <span>{{ num1 + num2 }}</span>
    <br />
    <input type="text" v-model.number="num3" /> +
    <input type="text" v-model.number="num4" /> =
    <span>{{ num3 + num4 }}</span>
    <!-- 걍 타입 number 해도됨 -->
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'bondu',
      num1: 0,
      num2: 0,
      num3: 0,
      num4: 0
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    myFunction() {
      console.log(this.userId)
    },
    changeData() {
      this.userId = 'abc'
    }
  }
}
</script>
