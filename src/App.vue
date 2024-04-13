<script setup lang="ts">
import profilePic from './assets/download.jpg';
</script>

<template>
  <div class="p-6 sm:p-12 md:p-24 flex flex-col items-center justify-center min-h-screen bg-gradient-to-r from-pink-500 to-indigo-500 rounded">
    <img :src="profilePic" alt="Profile Picture" class="w-32 h-32 rounded-full mb-4 shadow-lg" />
    <div class="text-center" style="font-family: Helvetica;">
      <h1 class="text-3xl font-bold text-white mb-4">Md Farmiziee Fazley</h1>
      <p class="text-lg text-gray-200">
        My student id is 22FTT1494 taking course WEB DEVELOPMENT. I like to explore the world of technology, from coding in Python to designing creative projects with Scratch. I have a passion for problem-solving and love learning new skills like web development and graphic design. Outside of school, I enjoy playing sports, volunteering in my community, and spending time with friends.
      </p>
      <h2 class="text-xl font-semibold text-white mt-8">Skills</h2>
      <ul class="text-lg text-gray-200">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Vue.js</li>
        <li>Python</li>
      </ul>
      <h2 class="text-xl font-semibold text-white mt-8">Contact</h2>
      <ul class="text-lg text-gray-200">
        <li>Email: example@example.com</li>
        <li>Phone: 123-456-7890</li>
        <li>Website: www.example.com</li>
      </ul>
    </div>
  </div>
</template>

<style>
</style>