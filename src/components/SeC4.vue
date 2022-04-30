<template>
    <section>
        <div class="header">
            <h3>PHASELLUS EGET METUS</h3>
            <h1>Forum Sections</h1>
            <div></div>
        </div>

        <div class="row">

            <div class="card">
                <div class="card_1"><i class="fa-solid fa-tower-broadcast"></i></div>
                <div><a href="#">News & Community</a></div>
            </div>

            <div class="card">
                <div class="card_1"><i class="fa-brands fa-apple"></i></div>
                <div><a href="#">Apple Forum</a></div>
            </div>

            <div class="card">
                <div class="card_1"><i class="fa-brands fa-windows"></i></div>
                <div><a href="#">Microsoft Forum</a></div>
            </div>

            <div class="card">
                <div class="card_1"><i class="fa-brands fa-android"></i></div>
                <div><a href="#">Android Forum</a></div>
            </div>

        </div>

        <div class="row">

            <div class="card">
                <div class="card_1"><i class="fa-solid fa-mug-hot"></i></div>
                <div><a href="#">General Discussion</a></div>
            </div>

            <div class="card">
                <div class="card_1"><i class="fa-solid fa-cubes"></i></div>
                <div><a href="#">App & Software</a></div>
            </div>

            <div class="card">
                <div class="card_1">
                <div>
                    <i class="fa-solid fa-laptop"></i>
                </div>
                </div>
                <div><a href="#">Gudget & Staff</a></div>
            </div>

            <div class="card">
                <div class="card_1"><i class="fa-solid fa-wrench"></i></div>
                <div><a href="#">Tutorials & Guide</a></div>
            </div>

        </div>

    </section>
</template>

<script>
export default {
    name: 'SeC4',
     
}

</script>

<style scoped lang="scss">
@import "../assets/data/HeaDer.scss";

section{
    padding-top: 100px;
    background-color: #f2f2f2;
    height: 900px;
    padding-left: 20%;
    padding-right: 20%;
}


.card{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: white;
    width: 250px;
    height: 250px;
}

.row{
    display: flex;
    justify-content: space-around;
    margin-top: 2em;
}

.card_1{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100px;
    height: 100px;
    background-color: #FF8D61;
    margin-bottom: 1em;
    border-radius: 50px;
    color: white;
    font-size: 3em;
    margin-bottom: 0.2em;
}

.card a{
    text-decoration: none;
    color: black;
    font-weight: 700;
    margin: 10px;
    font-weight: 900;
    font-size: 1.2em;
}


</style>