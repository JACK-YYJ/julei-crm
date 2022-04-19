<template>
  <div>
    <svg-icon icon-class="github" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'JuLeiGit',
  data() {
    return {
      url: 'https://juleitech.com/sy'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
