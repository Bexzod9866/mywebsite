<template>
  <div>
    <app-pageheader/>
    <nuxt/>
    <app-footer/>
  </div>
  
</template>

<script>
import AppPageheader from "@/components/pageheader"
import AppFooter from "@/components/footer"
export default {
  components: {
    AppPageheader,
    AppFooter
  }
}
</script>

<style lang="scss" scoped>

</style>