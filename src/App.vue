<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
/* Global Styles */
body {
  margin: 0;
  font-family: 'Arial', sans-serif; /* Universal font for the application */
  background-color: #a4a3a3; /* Light gray background */
}

h1, h2, h3, h4, h5, h6 {
  color: #13569a; /* Dark color for headers */
}

p {
  color: #024699; /* Dark color for paragraphs */
}

th {
  color: #204bd7; /* Dark color for table headers */
}

a {
  text-decoration: none; /* Remove underline from links */
}

a:hover {
  text-decoration: underline; /* Underline on hover for links */
}

/* You can add more global styles here */
</style>
