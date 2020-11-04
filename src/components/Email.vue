<template>
    <div class="sec">
        <h2>Contact</h2>
        <div class="mail" id="contact">
            <div class="mess">
                <h3>Sent us e-mail from more !</h3>
            </div>
            <div class="arr">
                <i class="fas fa-long-arrow-alt-right fa-2x"></i>
            </div>
            <div class="info">
                <h1>info@cdmarket.gr</h1>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Email'

}
</script>

<style>

.sec h2{
    display: flex;
    justify-content: center;
    margin-top: 20px;
    margin-bottom: 20px;
	color: #fb2274;
	text-transform: uppercase;
	font-size: 38px;
	word-spacing: 15px;
    letter-spacing: 5px;
    height: 4rem;
}

.mail{
    display: flex;
    justify-content: space-around;
    height: 15rem;
    flex-wrap: wrap;
}

.mail .mess{
    margin-top: 65px;
    letter-spacing: 3px;
    text-shadow: 2px 2px 5px #fb2274;
}

.mail .mess h3{
    border: 2px solid black;
    border-radius: 5px;
    box-shadow: 5px 10px 18px #fb2274;
    padding: 5px;
}

.mail .mess h3:hover{
    transform: scale(1.1);
    cursor: pointer;
}

.mail .info{
    margin-top: 65px;
    color: #fb2274;
    letter-spacing: 5px;
    text-shadow: 0 0 1px #000000, 0 0 1px#000000;
}

.mail .info h1{
    border: 3px solid black;
    box-shadow: 5px 10px 18px #fb2274;
    padding: 10px;
    border-radius: 5px;
}

.mail .arr{
    margin-top: 65px;
}

@media screen and (max-width: 720px){

    .mail .mess{
        margin: 0;
    }

    .mail .arr{
        display: none;
    }

    .mail .info{
        color: #fb2274;
        margin-top: 5px;
    }

}

</style>