<template>
  <p>Register for the event here</p>
  <button @click="register">Register me</button>
</template>

<script>
export default {
  props: ['event'],
  methods: {
    register() {
      this.$router.push({
        name: 'EventDetails',
      })
    }
  }
}
</script>
