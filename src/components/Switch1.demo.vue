<demo>
  示例：常规用法
</demo>
<template>
  <Switch v-model:value="bool"/>
</template>

<script lang="ts">
  import { Switch } from '../lib/index'
  import { ref } from 'vue'
  export default {
    name: 'SwitchDemo1',
    components: {
      Switch
    },
    setup(){
      const bool = ref(false)
      return { bool }
    }
  }
</script>
