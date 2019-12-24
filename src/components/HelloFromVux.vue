<template>
  <div>
    <div class="vux-demo">
      <img class="logo" src="../assets/vux_logo.png">
      <h1> </h1>
    </div>
    <group title="cell demo">
      <cell title="VUX" value="cool" is-link></cell>
    </group>
    <div class="text-my-dl">
      <div>上海</div>
      <div>广东</div>
      <div>深圳</div>
      <div>北京</div>
    </div>
  </div>
</template>

<script>
import { Group, Cell } from 'vux'

export default {
  components: {
    Group,
    Cell
  },
  data () {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>

<style>
.vux-demo {
  text-align: center;
}
.logo {
  width: 100px;
  height: 100px
}
.text-my-dl{
  display: flex;
  justify-content:space-between;
}
.text-my-dl div{
  width: 25%;
  border: 1px solid red;
  padding: 2%;
  border-radius: 0.2rem;
  color: green;
  text-align: center;
}
</style>
