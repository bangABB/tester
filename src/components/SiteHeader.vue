<template>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'SiteHeader'
}
</script>

<style scoped>
header {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 1rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
}
</style>
