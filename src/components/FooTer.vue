<template>
    <footer>
    <div class="first">    
        <div>
            <span class="copyR"><i class="fa-regular fa-copyright"></i></span>
            <span class="opacity"> Copyright 2012 - 2020 |  AVADA theme by </span>
            <span>Them fusion </span>
            <span class="opacity">| All Right Reserved | powered by</span>
            <span> WordPress</span>
        </div>

        <div class="logo">
            <div class="logo_card color_blue">
                <a href=""><i class="fa-brands fa-facebook-f"></i></a>   
            </div>
            <div class="logo_card color_azzurro">
                <a href=""><i class="fa-brands fa-twitter"></i></a> 
            </div>
            <div class="logo_card color_grigio">
               <a href="#"><i class="fa-brands fa-instagram"></i></a> 
            </div>
            <div class="logo_card color_red">
              <a href="#"><i class="fa-brands fa-youtube"></i></a>  
            </div>
        </div>
    </div>

        <div class="sign">
            <div>Write with </div> <div><i class="fa-solid fa-heart"></i></div> <div> by The Saint</div>
        </div>

    </footer>
</template>

<script>
export default {
    name: 'FooTer',
     
}

</script>

<style scoped lang="scss">

footer{

    padding: 2em 20% 2em 20%;
    height: fit-content;
}

.first{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
}

.logo{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    height: fit-content;
}

.logo_card{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 3em;
    width: 3em;
    border-radius: 50%;
    margin-right: 1em;
}

.logo_card>a>i{
    color: white;
}

.color_blue{
    background-color: #3C5998;
}

.color_azzurro {
    background-color: #54ACEE;
}

.color_grigio{
    background-color: #3F729B;
}

.color_red{
    background-color: #CD201F;
}

.copyR{
    font-size: 0.5em;
    vertical-align: top;
    opacity: 0.7;
}

.opacity{
    opacity: 0.7;
}

.sign{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 1.5em;
}

.sign i{
    font-size: 2em;
    margin-left: 0.3em;
    margin-right: 0.3em;
    color: red;
}

</style>