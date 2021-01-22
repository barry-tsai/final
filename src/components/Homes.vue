<template>
    <div>
	<div class="space"></div>
    <h1 class="flex-h1">
		<img src="~@/assets/guitar.jpg.gif" width="300">
		<h1 class="h1-1">
			夏日線索<br>
			Summer Clues
		</h1>
		<img src="~@/assets/piano.jpg.gif" width="280">
	</h1>
	<div class="space"></div>
    </div>
</template>

<script>
export default {
    data(){
		return{
		}
	}
};
</script>

<style lang="sass">
.flex-h1
	//border: solid blue
	flex-direction: row
	display: flex
	justify-content: center

.h1-1
	//border: solid red
	font-size: 50px
	height: 50px
	width: 600px
	text-align: center

.h1-1:hover
	transform: scale(1.5)

.space
	//border: solid red
	height: 210px

</style>
