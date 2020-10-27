<template>
    <div class="banner_image">
		<div class="banner_content">
			<h1>Only I can change my life.<br/><span>No one can do it for me.</span></h1>
			<p>You only live once, but if you do it right, once is enough.</p>
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
		width: 97%;
	}


	.banner_content{
		margin-top: 50px;
	}

}

@media (max-width: 850px){

	.banner_image .banner_content h1{
		margin-top: 60px;
		width: 95%;
   }

   .banner_content p{
		width: 22rem;
	}

}
</style>