<template>
    <section>
        <div class="header">
            <h3>PHASELLUS EGET METUS</h3>
            <h1>All the lates news</h1>
            <div></div>
        </div>
<!-- FIXME da fare un arrey di oggetti e farlo ciclare -->
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

        <!-- </div> -->
            <!-- <div><img :src="../assets/img/post_feat_img_25-320x202.jpg" alt="Telefonino"></div>
            <div><img :src="../assets/img/post_feat_img_24-320x202.jpg" alt=""></div>
            <div><img :src="../assets/img/post_feat_img_23-320x202.jpg" alt=""></div> -->

        <div class="SectOne">
            <!-- FIXME dinamiccizare i commeti -->
            <div>
                <img src="../assets/img/post_feat_img_25-320x202.jpg" alt="Telefonino uno">
                <h1>{{SectOneData[0].title}}</h1>
                <div class="commet">
                    <div>{{SectOneData[0].data}} :</div>
                    <div class="separazio"> | </div>
                    <div>{{SectOneData[0].comment}}</div>
<!-- NOTE provare a mettere l'array con il dollaro -->
                     <!-- :class="(SectOneData[0].comment == "2 comment") ? 'commentClass1' : 'commentClass2' " -->
                </div>
                <h4>{{SectOneData[0].text}}</h4>
            </div>

            <div>
                <img src="../assets/img/post_feat_img_24-320x202.jpg" alt="Telefonino due">
                <h1>{{SectOneData[1].title}}</h1>
                <div class="commet">
                    <div>{{SectOneData[1].data}}</div>
                    <div class="separazio"> | </div>
                    <div>{{SectOneData[1].comment}} class= </div>
                </div>
                <h4>{{SectOneData[1].text}}</h4>
            </div>

            <div>
                <img src="../assets/img/post_feat_img_23-320x202.jpg" alt="Orologio">
                <h1>{{SectOneData[2].title}}</h1>
                 <div class="commet">
                    <div>{{SectOneData[2].data}}</div>
                    <div class="separazio"> | </div>
                    <div>{{SectOneData[2].comment}}</div>
                </div>
                <h4>{{SectOneData[2].text}}</h4>
            </div>

        </div>


    </section>
</template>

<script>
import dataOne from '../assets/data/SectOne.json';

export default {

  name: 'SecThree',
    
    data(){
        return{
            SectOneData : dataOne,
        }

    }

}
</script>

<style scoped lang="scss">

    section{
        padding-top: 100px;
        padding-left: 20%;
        padding-right: 20%;
    }

    .header{
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .header>div{
        border: 2px solid orange;
        width: 5%;
        // background-image: ;
    }

    .SectOne{
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        text-align: left;
    }

    .SectOne>div{
        width: calc((100%/3) - 10px);
    }

    .SectOne>div>h1{
        font-size: 1em;
    }

     .SectOne>div>h4{
        font-size: 0.8em;
        opacity: 0.8;
        text-align: left;
        line-height: 1em;
    }

    .commet{
        display: flex;
        flex-wrap: wrap;
        font-size: 0.8em;
        margin-top: 1em;
        margin-bottom: 1em;
        opacity: 0.7;
    }

    .separazio{
        margin-left: 1em;
        margin-right: 1em;
    }

</style>