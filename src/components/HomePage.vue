<template>
    <div class="home-page">
      <div class="container text-center">
        <img
          src="../../images/university_logo.png"
          alt="University Logo"
          class="logo"
        />
        <h1 class="title">Welcome to Our Bank Management System</h1>
        <p class="subtitle">Manage your accounts with ease and security.</p>
        <router-link to="/accounts">
          <b-button variant="primary" size="lg" class="navigate-button">
            View Accounts
          </b-button>
        </router-link>
      </div>
    </div>
  </template>

  <script>
  export default {
    name: "HomePage",
  };
  </script>

  <style scoped>
  .home-page {
    height: 100vh; /* Full viewport height */
    display: flex;
    align-items: center; /* Center vertically */
    justify-content: center; /* Center horizontally */
    text-align: center;
  }

  .logo {
    max-width: 300px; /* Set a max width for the logo */
    margin-bottom: 20px; /* Space below the logo */
  }

  .title {
    font-size: 2.5rem; /* Large title */
    font-weight: bold; /* Bold title */
  }

  .subtitle {
    font-size: 1.25rem; /* Medium subtitle */
    margin-bottom: 30px; /* Space below the subtitle */
  }

  .navigate-button {
    padding: 10px 20px; /* Button padding */
    font-size: 1.25rem; /* Larger button text */
  }
  </style>
