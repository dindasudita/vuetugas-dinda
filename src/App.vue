<template>
  <div class="app" id="Main">
    <header>
      <div class="top">
        <Navbar />
        <div class="container">
          <div class="left">
            <LeftSection />
          </div>
          <RightSection />
        </div>
      </div>
    </header>
    <Buttonw />
    <div class="center" style="overflow-y: auto;">
      <About /> 
      <Skill /> 
      <Experience />
      <Contact />
  </div>
</div>
</template>


<script setup>
  import Navbar from './components/Navbar.vue'
  import Buttonw from './components/Buttonw.vue'
  import LeftSection from './components/LeftSection.vue'
  import RightSection from './components/RightSection.vue'
  import About from './views/About.vue'
  import Experience from './views/Experience.vue'
  import Skill from './views/Skill.vue'
  import Contact from './views/Contact.vue'
</script>

<style>

body {
    background-color: #fcf6f0;
    font-family: 'Rubik', sans-serif;
}

.center {
  text-align: center;
  margin-top:150px; 
  margin-bottom: 100px;
}

</style>
