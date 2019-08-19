<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <v-link class="nav-link" href="/">Home</v-link>
        </li>
      </ul>
    </nav>
    <div class="container">
      <slot></slot>
    </div>
  </div>
</template>

<script>
  import VLink from '../components/VLink.vue'

  export default {
    components: {
      VLink
    }
  }
</script>
