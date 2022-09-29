<template>
  <div class="flex flex-col h-screen">
    <nav class="navbar bg-base-100">
      <div class="flex-none">
        <button class="btn btn-square btn-ghost">
          <menu-icon />
        </button>
      </div>
      <div class="flex-1">
        <a class="btn btn-ghost normal-case text-xl"> Fanbox Assistant </a>
      </div>
      <div class="flex-none">
        <button class="btn btn-square btn-ghost">
          <dots-vertical-icon />
        </button>
      </div>
    </nav>

    <div class="hero h-full bg-base-200">
      <div class="hero-content text-center">
        <div class="max-w-md">
          <h1 class="text-5xl font-bold">Welcome to Fanbox Assistant</h1>
          <p class="py-6">Your assistant has been awaiting you for a while.</p>
          <button class="btn btn-primary">Get Started</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import MenuIcon from 'vue-material-design-icons/Menu.vue';
import DotsVerticalIcon from 'vue-material-design-icons/DotsVertical.vue';
</script>
