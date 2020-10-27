<template>
    <div class="arrow">
		<a href="#nav"><img v-bind:src="require('../assets/arrow.png')" alt="up_arrow" /></a>
	</div>
</template>



<script>
export default {
    name:'Arrow'
}
</script>


<style>

/* arrow */
.arrow{
	position: fixed;
	bottom: 25px;
	right: 25px;
	width: 40px;
	height: 40px;
	line-height: 50px;
	text-align: center;
	cursor: pointer;
	background: #fb2274;
	border-radius: 50%;
	color: blue;
	transition: width 0.5s, height 0.5s, transform 0.5s;
}

.arrow img{
	width: 20px;
	height: 20px;
	z-index: 1;
}

</style>