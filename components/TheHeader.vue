<template>
  <header
    class="flex items-center justify-between py-6 px-20 bg-gray-900 mb-4 text-white"
  >
    <div class="flex items-center">
      <h1 class="text-2xl font-bold">Notion</h1>
    </div>
    <div class="flex items-center ">
      <nav>
        <Nuxtlink to="/" :class="styles.link">Home</Nuxtlink>
        <Nuxtlink to="/" :class="styles.link">About</Nuxtlink>
        <Nuxtlink to="/" :class="styles.link">Contact</Nuxtlink>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'TheHeader',
  data() {
    return {
      styles: {
        link: 'py-2 px-6 rounded hover:bg-black/10 text-lg font-semibold ml-4 cursor-pointer'
      }
    }
  }
}
</script>
