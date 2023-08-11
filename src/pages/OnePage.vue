<template>

<q-page padding>
<pre>{{ myVar }}</pre>
</q-page>

</template>

<script>
import { ref } frome 'vue'


export default {
  data() {
     return{
       myVar: 'SomeMessage'

     }
   },
  setup () {
    const myVVar = ref('Some Message')

    return {
      myVar
    }

  }
}

</script>
