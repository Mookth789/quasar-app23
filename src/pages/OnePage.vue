<template>

<q-page padding>
<pre>{{ myVar }}</pre>
<q-input v-model="myVar"></q-input>
</q-page>

</template>

<script>
import { ref } frome 'vue'


export default {
  // data() {
  //    return{
  //      myVar: 'SomeMessage'

  //    }
  //  },
  setup () {
    const myVVar = ref('Some Message')

    return {
      myVar
    }
  }
}

</script>
