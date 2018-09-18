<template>
  <div id="app">
  </div>
</template>
<script>
import Vue from 'vue'
import { Component } from 'vue-class-component'
import Dog from './Dog' //Does not work! :(
@Component({
  data () {
  return {
    dog: new Dog()
  }
  },
  })
export default class App extends Vue {}
</script>
