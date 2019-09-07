<template>
  <section class="hero is-link is-fullheight-with-navbar">
    <div class="hero-body">
      <div class="container">
        <p class="title">
          {{sectionTitle}}
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FullPageSection',
  props: {
    sectionTitle: {
      type: String,
      required: true
    }
  },
  data () {
    return {
    }
  },
  computed: {
  },
  methods: {
  }
}
</script>

<style scoped>

</style>
