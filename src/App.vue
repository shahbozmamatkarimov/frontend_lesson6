<template>
  <div class="maincontainer">
    <header>
      <Navbar />
    </header>
    <Main />
  </div>
</template>

<script>
import { Navbar, Main } from './components'
export default {
  components: {
    Navbar,
    Main,
  }
}
</script>

<style lang="scss"></style>