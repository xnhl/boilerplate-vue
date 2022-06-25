<template>
  <div id="app">
    <HelloWorld msg="hello world" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'App',
  components: { HelloWorld }
}
</script>

<style lang="sass">
@font-face
	font-family: 'Open Sans'
	src: url('/fonts/OpenSans-Regular.ttf') format('truetype')
	font-weight: normal
	font-style: normal
#app
	font-family: 'Open Sans', 'Roboto', sans-serif
	font-size: 14px
	-ms-text-size-adjust: 100%
	-webkit-text-size-adjust: 100%
	-moz-osx-font-smoothing: grayscale
	-webkit-font-smoothing: antialiased
	box-sizing: border-box
*, *:before, *:after
	box-sizing: border-box
	font-size: 14px
	padding: 0
	margin: 0
	line-height: 1.1rem
</style>
