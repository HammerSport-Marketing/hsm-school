<template>
  <div>
    <Login />
  </div>
</template>

<script>
import Login from '~/components/Login'

export default {
  components: {
    Login,
  },
  data: () => ({
    alignments: ['center'],
  }),
}
</script>

<style lang="scss" scoped>
</style>