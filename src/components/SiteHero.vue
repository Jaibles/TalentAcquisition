<template>
  <div class="container-narrow mx-auto mt-20">
    <h1 class="md:pt-12">{{ msg }}</h1>
    <p class="text-lg mt-8">
      We're a fully remote service giving scaling businesses access to a dedicated Talent Acquisition team.
    </p>
    <p class="text-lg mt-4">
      Get Talent Acquisition for a fixed monthly fee, a fraction of the cost of a full-time resource. We become an extension of your business that you can leverage when you need it.
    </p>

    <AppButton class="mt-12 primary"
      link="https://talentacquisitionie.typeform.com/to/dKDMZE5W"
      msg="Get Started"
      target="_blank"
    />
    <AppButton class="mt-12 ml-2 tertiary" link="#why-us" msg="Learn more" />
  </div>
</template>

<script>
import AppButton from './ui/AppButton.vue'

export default {
  name: 'SiteHero',
  components: {
    AppButton
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
