<template>
    <section>
        <div class="header">
            <h3>PHASELLUS EGET METUS</h3>
            <h1>All the lates news</h1>
            <div></div>
        </div>
<!-- FIXME da fare un array di oggetti e farlo ciclare -->
        <br>
        <br>

        <!-- <div 
            v-for="(element, index) in SectOneData"
            :key="index"
            class="SectOne" -->
            <!-- > -->
        <!-- <div>
                        <img :src="{{this.element.image}}"  alt=""> -->
                        <!-- <img :src="${this.element.image}"  alt=""> -->
                        <!-- <img :src=`${this.element.image}`  alt=""> -->
                        <!-- <img :src=" `../assets/img/post_feat_img_${element.image}` "  alt="" >
            <div :style=" {backgroundImage: `url (../assets/img/post_feat_img_${element.image} )`  } "></div>                         -->
            <!-- <img :src="element.image"  alt="">
            <h1>{{element.title}}</h1>
            <h2>{{element.data}}</h2>
            <h3>{{element.comment}}</h3>
            <h4>{{element.text}}</h4>
        </div> -->

        <div class="SectOne">
            <!-- FIXME dinamiccizare i commeti -->
            <div>
<!-- <div class="img_1" :style=" { backgroundImage: `url(../assets/img/post_feat_img_25-320x202.jpg )` }"> -->
                <div class="img_1" :style=" { backgroundImage: `url(${SectOneData[0].image})` }"></div>

                    <!-- <img src="../assets/img/post_feat_img_25-320x202.jpg" alt="Telefonino due"> -->
                    <h1>{{SectOneData[0].title}}</h1>
                <div class="commet">
                    <div>{{SectOneData[0].data}} | {{SectOneData[0].comment}}</div>
<!-- NOTE provare a mettere l'array con il dollaro -->
                     <!-- :class="(SectOneData[0].comment == "2 comment") ? 'commentClass1' : 'commentClass2' " -->
                </div>
                <h4>{{SectOneData[0].text}}</h4>
            </div>

            <div>
                <!-- <img :src=" `${SectOneData[1].image}` " alt="Telefonino due"> -->
                <img src="../assets/img/post_feat_img_24-320x202.jpg" alt="Telefonino due">
                <h1>{{SectOneData[1].title}}</h1>
                <div class="commet">
                    <div>{{SectOneData[1].data}} | {{SectOneData[1].comment}}</div>
                </div>
                <h4>{{SectOneData[1].text}}</h4>
            </div>

            <div>
                <img src="../assets/img/post_feat_img_23-320x202.jpg" alt="Orologio">
                <h1>{{SectOneData[2].title}}</h1>
                 <div class="commet">
                    <div>{{SectOneData[2].data}} | {{SectOneData[2].comment}}</div>
                </div>
                <h4>{{SectOneData[2].text}}</h4>
            </div>
        </div>

        <div class="SectTwo">
                <div class="SectTwo_1">
                    <h3>{{SectTwoData[0]}}</h3>
                    <h1>{{SectTwoData[1]}}</h1>
                    <h5>{{SectTwoData[2]}}</h5>
                </div>
                <div class="SectTwo_Button">
                    <a href="#">READ MORE ></a>
                </div>
        </div>
        
        <br>
        <br>

    <div class="SectOne">
            <!-- FIXME dinamiccizare i commeti -->
            <div>
                <img src="../assets/img/post_feat_img_22-320x202.jpg" alt="Telefonino uno">
                <h1>{{SectOneData[0].title}}</h1>
                <div class="commet">
                    <div>{{SectOneData[0].data}}</div>
                    <div class="separazio"> | </div>
                    <div>{{SectOneData[0].comment}}</div>
                </div>
                <h4>{{SectOneData[0].text}}</h4>
            </div>

            <div>
                <img src="../assets/img/post_feat_img_21-320x202.jpg" alt="Telefonino due">
                <h1>{{SectOneData[1].title}}</h1>
                <div class="commet">
                    <div>{{SectOneData[1].data}}</div>
                    <div class="separazio"> | </div>
                    <div>{{SectOneData[1].comment}}</div>
                </div>
                <h4>{{SectOneData[1].text}}</h4>
            </div>

            <div>
                <img src="../assets/img/post_feat_img_20-320x202.jpg" alt="Orologio">
                <h1>{{SectOneData[2].title}}</h1>
                 <div class="commet">
                    <div>{{SectOneData[2].data}}</div>
                    <div class="separazio"> | </div>
                    <div>{{SectOneData[2].comment}}</div>
                </div>
                <h4>{{SectOneData[2].text}}</h4>
            </div>
        </div>
        
        <br>
        <br>

<div class="sectThree">

        <div class="sectThree_one">
            <div class="SectTwo_1">
                    <h3>{{SectTwoData[0]}}</h3>
                    <h1>{{SectTwoData[1]}}</h1>
                    <h5>{{SectTwoData[2]}}</h5>
            </div>
            <div class="SectTwo_Button">
                    <a href="#">READ MORE ></a>
            </div>
        
        </div>    
        
        <div class="sectThree_two">

            <h1>Tutorials & Guides</h1>

            <div class="sectThree_two_break"></div>
            
            <div class="sectThree_two_display">
                    <div>
                        <img src="../assets/img/post_feat_img_23-147x118.jpg" alt="Orologino">
                    </div>
                    <div>
                        <div class="sectThree_two_display_1">
                            {{SectOneData[2].title}}
                        </div>
                        <h5>{{SectOneData[1].data}} | {{SectOneData[2].comment}}</h5>
                    </div>
            </div>
            <br>
            <div class="sectThree_two_display">
                    <div>
                        <img src="../assets/img/post_feat_img_22-147x118.jpg" alt="Orologino">
                    </div>
                    <div>
                        <div class="sectThree_two_display_1">
                            {{SectOneData[2].title}}
                        </div>
                        <h5>{{SectOneData[1].data}} | {{SectOneData[2].comment}}</h5>
                    </div>
            </div>
            <br>
            <div class="sectThree_two_display">
                    <div>
                        <img src="../assets/img/post_feat_img_20-147x118.jpg" alt="Orologino">
                    </div>
                    <div>
                        <div class="sectThree_two_display_1">
                            {{SectOneData[2].title}}
                        </div>
                        <h5>{{SectOneData[1].data}} | {{SectOneData[2].comment}}</h5>
                    </div>
            </div>
            
        </div>
 
    </div>

        <br>
        <br>

</section>
</template>

<script>
import dataOne from '../assets/data/SectOne.json';
import dataTwo from '../assets/data/SectTwo.json';

export default {

  name: 'SecThree',
    
    data(){
        return{
            SectOneData : dataOne,
            SectTwoData: dataTwo,
        }

    }

}
</script>

<style scoped lang="scss">
@import "../assets/data/HeaDer.scss";

    section{
        padding-top: 100px;
        padding-left: 20%;
        padding-right: 20%;
    }


    .SectOne{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        text-align: left;
    }

    .SectOne>div{
        width: calc((100%/3) - 2em);
    }

    .SectOne>div>h1{
        font-size: 0.8em;
    }

     .SectOne>div h4{
        font-size: 0.8em;
        opacity: 0.6;
        text-align: left;
        line-height: 1.6;
    }

    .commet{
        display: flex;
        flex-wrap: wrap;
        font-size: 0.8em;
        margin-bottom: 1em;
        opacity: 0.6;
    }

    .separazio{
        margin-left: 1em;
        margin-right: 1em;
    }

    .SectTwo{
        margin-top: 2em;
        background-image: url('../assets/img/featured_article_1_bg.jpg');
        width: 100%;
        height: 550px;
        background-repeat: no-repeat;
        background-size: 100%;
        color: white;
        padding-top: 300px;
        padding-left: 200px;
        padding-right: 200px;
    }

    .SectTwo h1{
        margin-top: 1em;
        margin-bottom: 1em;
    }

    .SectTwo_Button{
        margin-top: 1em;
        background-color: black;
        padding: 1em 2em 1em 2em;
        width: fit-content;
    }

    .SectTwo_Button a{
        text-decoration: none;
        color: white;
    }

    .sectThree{
        display: flex;
        justify-items: space-around;

    }

    .sectThree_one{
        width: 65%;
        height: 500px;
        background-image: url('../assets/img/featured_article_2_bg.jpg');
        background-size: cover;
        margin-right: 1em;
        padding: 250px 200px 0px 200px;
        color: white;
    }

    .sectThree_two_break{
        margin-top: 1em;
        margin-bottom: 2em;
        width: 100px;
        border: 1px solid orange;
    }

    .sectThree_two_display{
        display: flex;
        flex-wrap: wrap;
        justify-items: start;
    }

    .sectThree_two_display_1{
        margin-left: 10px;
        font-size: 1em;
        word-wrap: break-word;
        width: 200px;
        font-weight: 900;
    }

    .sectThree_two_display>div h5{
        font-size: 0.8;
        margin-left: 10px;
        opacity: 0.6;
    }

     .img_1{
         width: 100%;
        //  background-image: url('../assets/img/post_feat_img_25-320x202.jpg');
         height: 202px;
     }

     .SectOne>div img{
         width: 100%;
     }


</style>