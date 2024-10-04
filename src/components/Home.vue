<template>
  <div class="home">
    <h1>Welcome to the IE Bank Page</h1>
    <button @click="goToAccounts">View Accounts</button>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  methods: {
    goToAccounts() {
      this.$router.push('/accounts')
    }
  }
}
</script>

<style scoped>
.home {
  text-align: center;
  padding: 20px;
}

button {
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
}
</style>