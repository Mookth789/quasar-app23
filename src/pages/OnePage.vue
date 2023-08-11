<template>

<q-page padding>
<pre>{{ myVar }}</pre>
  <q-input v-model="myVar">
  </q-input>

</q-page>
</template>

<script>
import { computed } frome '@vue/reactivity'
import { ref, computed } frome 'vue'


export default {

  setup () {
    const myVVar = ref('Some Message')

    const computedExample = computed(() => {
      return myVar.value + 'more text'
    })

    return {
      myVar
      
    }
  }
}

</script>
