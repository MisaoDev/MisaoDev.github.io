<template lang="pug">
h1 Hola mundo

.flex-col-gap
  o-button( @click="frogs++" ) Sapo
  span( v-if="frogs" ) Sapos: {{ frogs }}
</template>

<script>
export default {
  data() {
    return {
      frogs: 0,
    }
  },
}
</script>

<style lang="scss" scoped></style>
