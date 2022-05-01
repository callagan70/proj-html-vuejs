<template>
    <div id="header">

            <img src="../assets/img/logo.png" alt="Logo">
            <div class="headerUl">

                <div>
                    <div v-for="(element, index) in HeaderDatas" v-bind:key="index" class="list">

                        <div>    
                            <a href="#">{{element.name}}</a>
                        </div>

                        <div class="triangle">

                        </div>

                    </div>

                </div>

                <div class="lens">
                        <div><a href="#">JOIN US</a></div>
                        <a href="#"><i class="fa-solid fa-magnifying-glass"></i></a>
                </div>

            </div>


    </div>
</template>

<script>
import HeaderData from "../assets/data/HeaderData.json";


export default {
    name: 'HeaderComp',

    data(){
        return{
        HeaderDatas: HeaderData,

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
            justify-content: center;
        }

        .list{
                // display: flex;
                position: relative;
                // flex-direction: column;
                // align-items: center;            
        }

        .list:hover>div{
            display: block;
        }

                .triangle {
                    display: none;
                    position: relative;
                    width: 0;
                    height: 0;
                    border-left: 10px solid transparent;
                    border-top: 20px solid #26A9BD;
                    border-right: 10px solid transparent;
                    top: 50px;
                }


        .headerUl>div>div a{
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

        .lens i{
            width: 1em;
            color: white;
            margin-left: 3em;
        }

        .lens>div{
            background-color: black;
            padding: 10px 20px 10px 20px;
            border-radius: 5px;
        }

        .lens>div a{
            color: white;
            text-decoration: none;
        }

</style>