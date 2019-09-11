<template>
    <div>
        <div>{{ count }}</div>
    </div>
</template>
<script>
import {store} from '../store.js'
export default {
  name: 'count',
  computed: {
    count: function () {
	    return store.state.count
    },
  },
}

</script>