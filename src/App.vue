<template>
  <main class="p-2">
    <h1>Currently activated pages are {{ activePage }}</h1>
  </main>
</template>

<script>
export default {
  data() {
    return {
      activePage: 0
    }
  }
}
</script>
