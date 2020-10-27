<template>
    <div class="ourteam" id="ourteam">

		<h1 class="title">our team</h1>

		<div class="ourteam_wrapper">

			<div class="team1" id="team">
				<div class="team_members" data-name="nathan john"><img v-bind:src="require('../assets/team1.jpg')" alt="Team_Images" />
				</div>
				<div class="team_members" data-name="Alyssa Healy"><img v-bind:src="require('../assets/team2.jpg')" alt="Team_Images" />
                </div>
				<div class="team_members" data-name="Alec Stewart"><img v-bind:src="require('../assets/team3.jpg')" alt="Team_Images" />
				</div>
			</div>

			<div class="team2" id="team">
				<div class="team_members" data-name="Michael Rippon"><img v-bind:src="require('../assets/team3.jpg')" alt="Team_Images" />
				</div>
				<div class="team_members" data-name="Meg Lanning"><img v-bind:src="require('../assets/team4.jpg')" alt="Team_Images" />
				</div>
				<div class="team_members" data-name="Sophie Devine"><img v-bind:src="require('../assets/team4.jpg')" alt="Team_Images" />
				</div>
			</div>

		</div>

	</div>
</template>


<script>
export default {
    name:'Team'
}

</script>


<style scoped>

/* our team */
.ourteam{
    text-align: center;
    padding: 5% 10%;
    background: #f5f5f5;
}


h1.title{
	margin-bottom: 20px;
	color: #fb2274;
	text-transform: uppercase;
	font-size: 38px;
	word-spacing: 15px;
    letter-spacing: 5px;
}

.ourteam_wrapper{
	display: flex;
    flex-direction: column;
}

.ourteam_wrapper #team{
	display: flex;
	justify-content: space-between;
}

.ourteam_wrapper .team1 #team{
	margin-bottom: 25px;
}

.ourteam_wrapper .team_members{
	width: 25%;
	height: auto;
	cursor: pointer;
    overflow: hidden;
    position: relative;
    margin-bottom: 25px;
}

.ourteam_wrapper .team_members img{
	display: block;
	width: 100%;
	height: auto;
	transition: all 0.5s ease;
}

.ourteam_wrapper .team_members:hover img{
	transform: scale(1.1);
}

</style>