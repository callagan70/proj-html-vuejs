<template>
  <section>
      <h1>AVADA FORUM IS THE PLACE TO BE</h1>
      <h4>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia minima facere aut dignissimos labore distinctio quaerat, provident odio cum alias architecto dolorem ipsam eveniet ut sequi ad aliquam nesciunt earum.</h4>
  </section>
</template>

<script>
export default {
  name: 'SecTwo',
}
</script>

<style scoped lang="scss">
    section{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 300px;
        background-color: #F2F2F2;
    }
// FIXME aggiustare le dimensioni del testo e il grassetto 
    section h1{
        margin-bottom: 1em;
        font-size: 1em;
    }

        section h4{
            font-weight: 300;
            width: 30%;
            text-align: initial;
            font-weight: 300;
    }

</style>