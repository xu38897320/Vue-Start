<template>
  <div class="home">

    <button @click="go">to mine</button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {

  },
  methods: {
    go() {
      this.$router.push({ name: 'mine', query: { id: 1, name: 'xx' } });
      // this.$router.replace({ name: 'mine' });
    },
  },
};
</script>
