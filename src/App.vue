<template>
	<MainPage/>
</template>

<script>
import MainPage from './components/main-page/MainPage.vue'

export default {
	name:       'App',
	components: {
		MainPage,
	}
}
</script>

<style>
body {
	font-family:             "PT Sans", sans-serif;
	-webkit-font-smoothing:  antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align:              center;
	color:                   #fff;
}

a {
	text-decoration: none;
}
</style>
