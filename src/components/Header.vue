<template>
    <div class="navbar" id="nav">
			<div class="logo">
				<a href="/"><i class="fas fa-code"></i> Coding Market</a>
			</div>
			<div class="navbar_items">
				<ul>
					<li><a href="#about">about</a></li>
					<li><a href="#services">services</a></li>
					<li><a href="#ourteam">our team</a></li>
				</ul>
			</div>
		</div>
</template>



<script>
export default {
    name:'Header'

}

</script>



<style scoped>

/* Navigation Bar */
.navbar{
	width: 100%;
	height: 65px;
	position: absolute;
	display: flex;
	justify-content: space-around;
	align-items: center;
}

.logo a{
	font-size: 32px;
	color: #fb2274;
}

.logo:hover{
	transform: scale(1.1);
}

.navbar_items ul{
	display: flex;
}

.navbar_items:hover{
	transform: scale(1.1);
}

.navbar_items ul li{
	margin: 0 10px;
}

.navbar_items ul li a{
	text-transform: uppercase;
	color: #fff;
	padding: 10px;
}

.navbar_items ul li a:hover{
	color: #fb2274;
}


@media (max-width: 720px){

	.navbar{
		height: auto;
		flex-direction: column;
	}

	.logo{
		margin-top: 10px;
	}

	.navbar_items ul{
		flex-direction: column;
		text-align: center;
		margin-top: 20px;
	}

	.navbar_items ul li{
		margin-top: 45px;
		padding: 10px;
	}

	.navbar_items:hover{
		transform: scale(1.1);
	}
}
</style>