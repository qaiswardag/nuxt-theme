<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <header>
    <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
      <div class="w-full py-6 flex items-center justify-between border-b border-indigo-500 lg:border-none">
        <NuxtLink to="/" class="text-purple-800 text-4xl">logo</NuxtLink>
        <span class="sr-only">Workflow</span>

        <div class="flex items-center">
          <div class="hidden ml-10 space-x-8 lg:block">
            <NuxtLink to="/" class="text-base font-medium hover:text-pink-600">Home page</NuxtLink>
            <NuxtLink to="/products" class="text-base font-medium hover:text-pink-600">Products</NuxtLink>
          </div>
        </div>
        <div class="ml-10 space-x-4">
          <NuxtLink to="/auth/login" class="inline-block bg-indigo-500 py-2 px-4 border border-transparent rounded-md text-base font-medium text-white hover:bg-opacity-75">Sign in</NuxtLink>
          <NuxtLink to="/auth/register" class="inline-block bg-white py-2 px-4 border border-transparent rounded-md text-base font-medium text-indigo-600 hover:bg-indigo-50">Sign up</NuxtLink>
        </div>
      </div>
      <div class="py-4 flex flex-wrap justify-center space-x-6 lg:hidden">
        <NuxtLink to="/" class="text-base font-medium hover:text-pink-600">Home page</NuxtLink>
        <NuxtLink to="/products" class="text-base font-medium hover:text-pink-600">Products</NuxtLink>
      </div>
    </nav>
  </header>
</template>

<script>

export default {
  name: 'Header',
}
</script>
