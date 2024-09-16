<template>
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/contact">Contact</router-link></li>
      </ul>
    </nav>
  </template>
  
  <style scoped>
  nav {
    background-color: #333;
    padding: 1rem;
  }
  
  ul {
    list-style: none;
    display: flex;
    gap: 1rem;
  }
  
  li {
    margin: 0;
  }
  
  a {
    color: white;
    text-decoration: none;
  }
  
  a.active {
    font-weight: bold;
  }
  </style>
  
<script>
export default {
    name: 'nav-component',
}
</script>
