<template>
    <section>
        <h2>Subscribe to our Newletter</h2>
        <div>
            <input type="text" placeholder="Insert your email">
            <span>SEND</span>
        </div>

    </section>
</template>

<script>
export default {
    name: 'SeC6',
     
}

</script>

<style scoped lang="scss">

section{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    background-color: #F2F2F2;
    width: 100%;
    height: 300px;
}

section>div{
    margin-top: 2em;
}

section>div>span{
    margin-left: 1em;
    padding: 7px 48px 7px 48px;
    background-color: black;
    color: white;
    font-weight: 700;
    font-size: 0.8em;
}

section>div>input{
    padding: 7px 16px 7px 16px;
    border: 0px solid white;
    width: 400px;
}

</style>