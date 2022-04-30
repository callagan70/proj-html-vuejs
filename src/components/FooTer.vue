<template>
    <footer>
        <div>
            <span><i class="fa-regular fa-copyright"></i></span> <span> Copyright 2012 - 2020 | </span> <span> AVADA theme fusion </span>  <span>| All Right Reserved | powered by</span> <span> WordPress</span>
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
    </footer>
</template>

<script>
export default {
    name: 'FooTer',
     
}

</script>

<style scoped lang="scss">

footer{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    padding: 2em 20% 2em 20%;
    height: fit-content;
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

</style>