<template lang='pug'>
v-app
  v-app-bar(app='' color='primary' dark='')
  v-main
    v-card.d-flex
      v-card-title v-card title 1
    v-card.d-flex
      v-card-title v-card title 2
        
</template>

<script lang='ts'>
import { VApp, VImg, VAppBar, VSpacer, VIcon, VBtn } from 'vuetify/lib'
import { Vue, Component, Prop } from 'vue-property-decorator'

@Component({
  components: {}
})
export default class App extends Vue { }
</script>
