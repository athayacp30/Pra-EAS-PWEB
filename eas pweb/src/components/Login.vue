<template>
  <div class="home">
    <h1>Welcome to the Chat App</h1>
    <div class="login-form">
      <input type="text" v-model="username" placeholder="Enter username" />
      <input type="password" v-model="password" placeholder="Enter password" />
      <button @click="login">Login</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      username: '',
      password: '',
    };
  },
  methods: {
    login() {
      // Implement login logic here
      // For example, set a logged-in state or make an API request to authenticate
      // Upon successful login, navigate to the channel creation or list of channels
      // You can use Vue Router to navigate to different pages upon successful login
    },
  },
};
</script>

<style scoped>
.home {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.login-form {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
</style>
