<template>
  <header>
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <RouterLink class="navbar-brand" to="/">
          <!-- Replace the text with your logo image -->
          <img src="https://lh3.googleusercontent.com/ogw/ANLem4YMF5Y6jI9sasTmri-BT_dPSASXFewMgcudVnLqrA=s32-c-mo" alt="Logo" style="max-height: 40px;" class="rounded-circle">
        </RouterLink>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <RouterLink class="nav-link" to="/">Home</RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink class="nav-link" to="/about">About</RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink class="nav-link" to="/login">LogIn</RouterLink>
            </li>
          </ul>
          <form class="d-flex">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router';
// Import your components as needed
</script>

<style scoped>
/* Add any necessary styles */
.container {
  margin-top: 40px; /* Adjust the margin as needed */
}
</style>
