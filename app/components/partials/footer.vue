<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://twitter.com/teffllc">
       <p>Copyright &copy; Teff LLC, Forever</p> 
      </a>
    </div>

  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: #8bd71a;
}
</style>
