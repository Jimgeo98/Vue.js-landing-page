<template>
    <div class="services" id="services">
		<h1 class="title">our Services</h1>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam quia, porro repellendus dolore
			repudiandae, accusantium corporis harum vel iste suscipit maiores provident ullam itaque libero minus
			nesciunt consequatur iusto numquam asperiores quod fugiat veniam blanditiis.
        </p>

		<div class="diff_services">

            <div class="diff_services_item">
                <img v-bind:src="require('../assets/services-1.png')" alt="service-image" />
                <h3 class="sub_title">Web Development</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            </div>

            <div class="diff_services_item">
                <img v-bind:src="require('../assets/services-2.png')" alt="service-image" />
                <h3 class="sub_title">App Development</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            </div>

            <div class="diff_services_item">
                <img v-bind:src="require('../assets/services-3.png')" alt="service-image" />
                <h3 class="sub_title">PSD to HTML</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            </div>

		</div>
	</div>

</template>


<script>

export default {
    name:'Services'
}

</script>


<style scoped>

/* Services */

h1.title{
	margin-bottom: 30px;
	color: #fb2274;
	text-transform: uppercase;
	font-size: 38px;
	word-spacing: 25px;
	letter-spacing: 5px;
}


.services{
	text-align: center;
    padding: 5% 10%;
    background: #f5f5f5;
}


.diff_services {
    margin-top: 35px;
    display: flex;
	justify-content: space-between;
}


.diff_services .diff_services_item {
	width: 30%;
}


.diff_services .diff_services_item img {
    width: 100%;
	margin-bottom: 25px;
	cursor: pointer;
    border-radius: 15px;
}


.diff_services .diff_services_item img:hover{
	transform: scale(1.1);
}


.diff_services .diff_services_item h3 {
    color: #fb2274;
    margin-bottom: 15px;
}


@media (max-width: 720px){

	.diff_services_item .sub_title{
		font-size: 14px;
	}

}

</style>