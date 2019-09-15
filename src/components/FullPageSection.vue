<template>
  <section class="hero work-in-progress is-fullheight-with-navbar" :style="{'background-color': mainColor}">
    <div class="hero-body">
      <div class="container">
        <p class="title is-1">
          {{sectionTitle}}
        </p>
        <slot></slot>
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
    },
    mainColor: {
      type: String,
      required: true
    }
  },
  data () {
    return {}
  },
  computed: {},
  methods: {}
}
</script>

<style scoped>
</style>
