<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-6">
        <div class="card">
          <div class="card-header">Login</div>
          <div class="card-body">
            <form @submit.prevent="login">
              <div class="mb-3">
                <label for="username" class="form-label">Username:</label>
                <input v-model="username" type="text" class="form-control" id="username" required>
              </div>
              <div class="mb-3">
                <label for="password" class="form-label">Password:</label>
                <input v-model="password" type="password" class="form-control" id="password" required>
              </div>
              <button type="submit" class="btn btn-primary">Login</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// const username = ref('');
// const password = ref('');

// const login = () => {
//   // Perform authentication logic here
//   // For simplicity, let's just log the entered username and password
//   console.log('Username:', username.value);
//   console.log('Password:', password.value);
// };
</script>

<style scoped>
/* Add any necessary styles */
</style>
