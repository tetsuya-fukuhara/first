<template>
  <div>
    <p>test<span>-</span>page</p>
    <app-logo />
    {{ test }}
  </div>
</template>
<script>
import AppLogo from '~/components/Logo.vue'
export default {
  components: {
    AppLogo
  },
  data() {
    return {
      test: 'test'
    }
  }
}
</script>
<style lang="scss" scoped>
p {
  font-size: 24px;
  span {
    color: red;
  }
}
</style>
