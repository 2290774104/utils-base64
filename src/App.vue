<template>
  <picture-base64 />
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import PictureBase64 from '@/components/picture-base64.vue'

@Options({
  components: {
    PictureBase64
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">

</style>
