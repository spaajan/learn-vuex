<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Counter />
    <CounterSquared />
    <Buttons />
    <ColorInput />
  </div>
</template>

<script>
// $store.commit hakee mutationin
// $store.dispatch hakee actionin
import Counter from '../components/Counter'
import CounterSquared from '../components/CounterSquared'
import Buttons from '../components/Buttons'
import ColorInput from '../components/ColorInput'

export default {
  name: 'Home',
  
  components: {
    Counter,
    CounterSquared,
    Buttons,
    ColorInput
  },
  methods: {
    
  }
}
</script>

<style>
  div {
    margin-bottom: 10px;
  }
  .counter {
    font-size:80px;
  }
  .buttons button {
    font-size:40px;
    width:100px;
    margin:0 10px;
  }
</style>