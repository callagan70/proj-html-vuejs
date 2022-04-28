<template>
    <div id="header">

            <img src="../assets/img/logo.png" alt="Logo">
            <div class="headerUl">
                    <div v-for="(element, index) in ListName" v-bind:key="index">
                        <a href="#">{{element.name}}</a>
                    </div>
                    <div class="lens">
                        <div>JOIN US</div>
                        <img src="../assets/img/icons-search.svg" alt="" >
                    </div>
            </div>


    </div>
</template>

<script>

export default {
    name: 'HeaderComp',

    data(){
        return{
        ListName:[ 
            {
                name: 'Home'
            }, 
            {
                name: 'Apple'
            }, 
            {
                name: 'Microsoft'
            }, 
            {
                name: 'Android'
            }, 
            {
                name: 'Forum'
            }, 
            {
                name: 'Contact Us'
            },] 
       }
       
    },
        
}

</script>

<style scoped lang="scss">
        #header{
            display:flex;
            justify-content: space-between;
            align-items: center;
            height: 100px;
            width: 100%;
            background-color: #26A9BD;
            padding: 2em 20em 2em 20em;
        }
             
         .headerUl{
             display: flex;
             flex-wrap: wrap;
             justify-content: flex-start;
             width: fit-content;
             height: fit-content;
         }
    
        .headerUl>div{
            display: flex;
            align-items: center;
        }

        .headerUl>div>a{
            color: white;
            text-decoration: none;
            margin-right: 2em;
        }

        .lens{
            display: flex;
            justify-content: end;
            align-items: center;
            margin-left: 1em;
        }

        .lens img{
            width: 1em;
            color: white;
            margin-left: 3em;
            cursor: help;
        }

        .lens>div{
            color: white;
            background-color: black;
            padding: 10px 20px 10px 20px;
            border-radius: 10px;
            cursor: pointer;
        }


</style>