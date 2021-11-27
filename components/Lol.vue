<!-- Please remove this file from your project -->
<template>
  <h1>Lol {{ num }}</h1>
</template>

<script>
export default {
  props: {
    num: {
      type: Number,
      required: true
    }
  }
}
</script>
