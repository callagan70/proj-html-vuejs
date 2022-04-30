<template>
    <section>

            <div>
                <h1>AVADA TECH FORUM</h1>
                <h3>Sed semper, nisl id feugiat eleifend, erat est digssim felic, quis auctor elit enim nec ante. Cras et nibh risus. Pellentesque non mi sit amet mi intermentum</h3>
            </div>

            <div>
                <h1>POPULAR TOPICS</h1>
                <div class="cont_topic">
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Nam a dolor volutpat massa auctor semper</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Sed euismod nunc urna fermentum aurcu dapibus fringilla</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Cras lacinia telluus id mauris finibus lacus molestie</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Curabitus a scelerisque ligula</a>
                                </div>
                        </div>
                </div>
            </div>

            <div>
                <h1>RECENT TOPICS</h1>
                <div class="cont_topic">
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Cras lacinia telluus id mauris finibus lacus molestie</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Sed euismod nunc urna fermentum aurcu dapibus fringilla</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Cras lacinia telluus id mauris finibus lacus molestie</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Curabitus a scelerisque ligula</a>
                                </div>
                        </div>
                </div>
            </div>

            <div>
                <h1>LATEST REPLIES</h1>
                <div class="cont_topic">
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Nam a dolor volutpat massa auctor semper</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Sed euismod nunc urna fermentum aurcu dapibus fringilla</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Cras lacinia telluus id mauris finibus lacus molestie</a>
                                </div>
                        </div>
                        <div class="topic">
                                <div>
                                    >
                                </div>
                                <div class="topic_2">
                                    <a href="#">Curabitus a scelerisque ligula</a>
                                </div>
                        </div>
                </div>
            </div>

    </section>
</template>

<script>
export default {
    name: 'SeC7',

}

</script>

<style scoped lang="scss">

section{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding-top: 100px;
    height: 500px;
    padding-left: 20%;
    padding-right: 20%;
    border-bottom: 2px solid #EAEAEA;
}

section>div{
    width: calc((100%/4) - 16px)
}

section>div>h3{
    font-size: 0.8em;
    opacity: 0.5;
    margin-top: 3em;
}

.topic{
    display: flex;
    flex: wrap;
    border-bottom: 1px solid #EAEAEA;
    padding: 1em 0px 1em 0px;
}

.topic_2{
    margin-left: 1em;
    color: white;
}

.topic_2 a{
       color: black;
       text-decoration: none;
       line-height: 1em;
       word-wrap: break-word;
       text-align: left;


}

.cont_topic{
    margin-top: 2em;
    
}


</style>