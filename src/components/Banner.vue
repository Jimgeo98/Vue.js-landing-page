<template>
    <div class="banner_image">
		<div class="banner_content">
			<h1 class="animate__animated animate__bounceInLeft">Only I can change my life.<br/><span>No one can do it for me.</span></h1>
			<p class="animate__animated animate__bounceInRight">You only live once, but if you do it right, once is enough.</p>
		</div>
	</div>
</template>

<script>
export default {
    name:'Banner'

}
</script>

<style scoped>

/* banner_image */

.banner_image{
    background: url("../assets/p3.jpg") no-repeat top center;
	background-size: cover;
    width: 100%;
	height: 900px;
	display: flex;
	justify-content: center;
	align-items: center;
}


.banner_content{
	text-align: center;
	color: #fff;
}


.banner_content h1{
	text-transform: uppercase;
	line-height: 38px;
	margin-bottom: 35px;
	font-size: 40px;
	text-shadow: 0 0 10px #000, 0 0 5px#001aff;
}

.banner_content p{
	font-size: 20px;
	text-shadow: 0 0 10px #000, 0 0 5px #001aff;
}


.banner_content h1 span{
	color: #fb2274;
}

.banner_image .banner_content p{
	color: #fff;
}


@media (max-width: 720px){

	.banner_image .banner_content h1{
		margin-top: 23px;
		width: 92%;
	}


	.banner_content{
		margin-top: 50px;
	}

}

@media (max-width: 850px){

	.banner_image .banner_content h1{
		margin-top: 100px;
		width: 95%;
   }

   .banner_content p{
		width: 22rem;
	}

}
</style>