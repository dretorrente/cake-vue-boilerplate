<template>
  <ul>
  <li v-for="anime in animes">
  {{anime}}
  </li>
  </ul>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      animes: ['One piece','Naruto','Bleach']
    }
  }
}
</script>
