<template>
  <div id="app">
    <SiteHeader />
    <AboutMe />
    <ProjectList />
    <ContactInfo />
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue'
import AboutMe from './components/AboutMe.vue'
import ProjectList from './components/ProjectList.vue'
import ContactInfo from './components/ContactInfo.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
    AboutMe,
    ProjectList,
    ContactInfo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
