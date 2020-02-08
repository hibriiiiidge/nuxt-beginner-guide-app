<template>
  <div>
    <p>
      User ID: {{ userID }}
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userID: this.$route.params.id
    }
  }
}
</script>
