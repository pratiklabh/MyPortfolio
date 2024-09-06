<script setup>
import AboutMe from "@/components/AboutMe.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <ul class="nav-list">
          <li><a href="#about">About Me</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#experience">Experience</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <AboutMe />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
  padding: 1rem;
  background-color: #fff;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.logo {
  display: block;
  width: 100px;
  margin: 0 auto 2rem;
}

.nav-list {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: space-around;
  margin-top: 1rem;
}

.nav-list li {
  display: inline;
}

.nav-list a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  padding: 0.5rem 1rem;
  transition: color 0.3s ease;
}

.nav-list a:hover {
  color: #007BFF;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .logo {
    width: 150px;
    margin: 0;
  }

  .nav-list {
    margin: 0;
  }
}
</style>
