<template>
  <section>
      <div>
        <h1>Tech Forum!</h1>
        <h3>Discuss all the lates tecnology news and trends</h3>
        <div>GET AWADA NOW: ></div>
      </div>

  </section>
</template>

<script>
export default {
  name: 'SecOne',



}
</script>

<style scoped lang="scss">
    section{
        background-image: url('../assets/img/home_slider_bg.jpg');
        background-repeat: no-repeat;
        width: 100%;
        height: 880px;
        color: white;
        padding-top: 20%;
        padding-left: 20%
    }

    section>div{
        width: fit-content;
    }

    section>div>h1{
        font-size: 10em;
    }

    section>div>h3{
        font-size: 1.85em;
        margin-top: 1em;
    }

     section>div>div{
        font-size: 1.85em;
        margin-top: 1em;
        padding: 15px;
        background-color: #26A9BD;
        width: fit-content;
        font-weight: 700;
    }

</style>