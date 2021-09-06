<template lang='pug'>
  .home Home
    //- img(alt='Vue logo' src='../assets/logo.png')
</template>

<script lang='ts'>
// @ is an alias to /src
import HelloWorld from './HelloWorld.vue'
import { Vue, Component, Prop } from 'vue-property-decorator'

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue { }
</script>
