<template>
  <div>888888888
    <button @click="back">返回</button>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {
    back() {
      this.$router.go(-1);
    },
  },
  mounted() {
    console.log(this.$route.query.id);
  },
};
</script>

<style>
</style>
