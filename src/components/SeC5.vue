<template>
    <section>
        <div>
            <h1>Hei!, Join to our Community</h1>
            <h4>Nulla molestie tortur nec lectus venantis, sed blandit dui finibus. Curabitur feugiat vulputate purus ipsums dolores ficilis uns etra.</h4>
            <div class="button">
                <a href="#">
                    SIGN UP >
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SeC5',
     
}

</script>

<style scoped lang="scss">

section{
    display: flex;
    justify-content: center;
    align-items:  center;
    width: 100%;
    height: 700px;
    background-image: url('../assets/img/join_now_cta_bg.jpg');
    background-repeat: no-repeat;
    color: white;
}

section>div{
    display: flex;
    justify-content: center;
    align-items:  center;
    flex-direction: column;
    width: 30%;
}

section>div>h1{
    font-size: 3em;
    text-align: center;
    margin-bottom: 1em;
    font-weight: 900;
}

section>div>h4{
    text-align: center;
    margin-bottom: 1em;
        font-weight: 500;
}

section>div>div>a{
    text-decoration: none;
    color: white;
};

.button{
    margin-top: 1em;
    padding: 1em 2em 1em 2em;
    width: fit-content;
    background-color: #26A9BD;
}

</style>