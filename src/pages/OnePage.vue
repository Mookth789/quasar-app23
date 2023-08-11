<template>

<q-page padding>
<pre>{{ myVar }}</pre>
  <q-input v-model="myVar">
  </q-input>

</q-page>
</template>

<script>
// import { ref } frome 'vue'


export default {

  setup () {
    const myVVar = ref('Some Message')

    const computedExample = computed(() => {
      myVar.value
    })

    return {
      myVar
    }
  }
}

</script>
