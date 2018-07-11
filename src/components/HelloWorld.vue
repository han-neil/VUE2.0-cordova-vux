<template>
  <div class="hello">
    <group>
      <cell title="首页" value="分享"></cell>
    </group>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
import { Group, Cell } from 'vux'
export default {
  name: 'HelloWorld',
  components: {
    Group,
    Cell
  },
  data () {
    return {
      msg: 'vue2.0+cordova+vux'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
