<template>
  <div>
    <svg-icon icon-class="question" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'Doc',
  data() {
    return {
      url: 'http://doc.kevinwong.tech'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>