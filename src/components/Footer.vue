<template>
    <div class="footer">
		<h4>Copyright &copy; 2020 Coding Market</h4>
	</div>
</template>


<script>
export default {
    name:'Footer'
}
</script>


<style>

/* footer */

.footer{
	width: 100%;
	text-align: center;
	background: #444444;
	padding: 20px 0;
}


.footer{
	height: 80px;
}


.footer h4{
	color: #fb2274;
	letter-spacing: 3px;
	margin-top: 12px;
}


@media (max-width: 720px){

	.footer h4{
		font-size: 12px;
	}

}

</style>