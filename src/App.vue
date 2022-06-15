<template>
  <TheHeader />
  <RouterView />
  <font-awesome-icon icon="trash-alt" />
</template>

<script>
import TheHeader from '~/components/TheHeader'

export default {
  components: {
    TheHeader
  }
}
</script>
