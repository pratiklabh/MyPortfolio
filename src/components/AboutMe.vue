<script setup>
import Title from "@/components/Title.vue";
import Paragraph from "@/components/Paragraph.vue";
</script>

<template>
  <section class="about-section">
    <div class="about-container">
      <Title text="About Me" />
      <div class="about-content">
        <img src="@/assets/me.webp" alt="Profile Image" class="profile-image" />
        <div class="text-content">
          <Title text="Pratik Kumar Labh" />
          <Paragraph text="Hello! I'm Pratik Kumar Labh, a passionate Computer Engineering graduate and Java enthusiast. I love exploring new technologies and building projects that solve real-world problems." />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about-section {
  padding: 1rem;
  background-color: #f9f9f9;
}

.about-content {
  display: flex;
  align-items: flex-start;
  gap: 20px; /* Space between image and text container */
}

.profile-image {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
}

.text-content {
  display: flex;
  flex-direction: column;

}

p {
  text-align: left;
  margin: 0;
}
</style>
