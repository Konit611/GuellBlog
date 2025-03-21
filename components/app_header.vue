<template>
  <div class="bg-gray-100 p-4">
    <nav class="flex justify-between w-full">
      <div class="flex items-center">
        <NuxtLink to="/">
            <img src="~/assets/logo_light.png" alt="" class="h-8 w-auto">
        </NuxtLink>
      </div>
      <div class="flex items-center space-x-6">
        <NuxtLink to="/about" class="nav-link">About</NuxtLink>
        <NuxtLink to="/blog" class="nav-link">Blog</NuxtLink>
        <NuxtLink to="/project" class="nav-link">Project</NuxtLink>
      </div>
      <div class="flex items-center space-x-2">
        <p>🇺🇸</p>
        <p>Dark</p>
      </div>
    </nav>
  </div>
</template>