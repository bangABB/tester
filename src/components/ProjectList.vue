<template>
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1</h3>
      <p>Description of project 1.</p>
    </div>
    <div class="project">
      <h3>Project 2</h3>
      <p>Description of project 2.</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectList'
}
</script>

<style scoped>
#projects {
  background-color: #f4f4f4;
  border: 1px solid #ddd;
  border-radius: 5px;
  padding: 2rem;
  margin: 1rem 0;
}

.project {
  margin-bottom: 1rem;
}
</style>
