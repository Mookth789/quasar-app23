<template>

<q-page padding>
One Page
</q-page>

</template>

<script>
import { ref } from 'vue'
export default {
  setup () {
    const myVar = ref('Some Messagr')
  }
  return {
    myVar
  }
}

</script>