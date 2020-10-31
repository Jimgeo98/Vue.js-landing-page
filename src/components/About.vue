<template>
    <div className="us"  id="about">
			<h1 className="title">About Us</h1>
			<div className="about">
				<div className="cont">
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Omnis, eveniet temporibus reprehenderit. Veniam
						sunt corrupti necessitatibus quam, quia doloribus nesciunt ut eveniet, alias aspernatur eum perferendis
						commodi doloremque recusandae tenetur quis cumque voluptatibus officiis ea excepturi dignissimos!
						Repellat molestias iusto dicta facere ipsum, harum maiores illum laborum tenetur? Explicabo, cupiditate!
						Morbi vulputate purus ornare, dictum lacus et, faucibus dolor. Sed et libero maximus, varius nisl id, porttitor ante.
						Etiam at lorem sed massa lacinia finibus eget sit amet nunc. Fusce in fermentum eros, nec cursus ligula.
						Quisque condimentum nec risus nec ultricies. Nullam molestie eleifend mattis. Nullam ut vehicula ex.
						In fermentum accumsan felis, in interdum mi dignissim sed. Duis elementum ac ante maximus aliquet.
						Duis at arcu vel turpis dictum ornare vitae eget diam. Duis vel suscipit libero, eu ultricies velit.
						Morbi vulputate purus ornare, dictum lacus et, faucibus dolor. Sed et libero maximus, varius nisl id, porttitor ante.
						In id nibh interdum, condimentum purus id, tempor metus. Integer et turpis ut odio convallis elementum. Aenean ut varius ipsum.
						Aliquam in pretium dolor, id ultrices ligula. Nam mattis sollicitudin est,
						ac lacinia lorem iaculis convallis. Phasellus commodo augue eu nisi lacinia, ut posuere ante tristique.
					</p>
				</div>
				<div className="image">
					<img v-bind:src="require('../assets/aboutimg.jpg')" alt="about-image" />
				</div>
			</div>
		</div>
</template>


<script>
export default {
	name:'About',
}

</script>



<style scoped>

/* About */

.us{
	height: 50rem;
}

.us .about{
    text-align: center;
	padding: 5% 10%;
	display: flex;
	justify-content: space-between;
}

.us .about img{
	width: 90%;
	border-radius: 20px;
	margin-left: 10px;
}

.us .about img:hover{
	transform: scale(1.1);
	cursor: pointer;
}

.us h1.title{
	margin-bottom: 25px;
	color: #fb2274;
	text-transform: uppercase;
	font-size: 38px;
	word-spacing: 15px;
	letter-spacing: 5px;
	margin-top: 50px;
	display: flex;
	justify-content: center;
}

.us .cont{
	margin-bottom: 15px;
	font-size: 16px;
	line-height: 20px;
	color: #242121;
}


@media screen and (max-width: 1300px){
	.us .about{
		flex-wrap: wrap;
	}

	.us .about img{
		width: 60%;
		margin-top: 20px;
	}
}


</style>