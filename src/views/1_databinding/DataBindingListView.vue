<template>
  <div>
    <select name="" id="">
      <option :value="city.code" :key="city.code" v-for="city in cities">
        {{ city.title }}
      </option>
    </select>
  </div>
  <!-- 테이블에 넣을 리스트 데이터 -->
</template>

<script>
export default {
  components: {},
  data() {
    return {
      cities: [
        { title: '서울', code: '02' },
        { title: '부산', code: '051' },
        { title: '제주', code: '064' }
      ]
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
