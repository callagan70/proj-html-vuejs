<template>
<div>
  <HeaderComp />
    <main>
      <SecOne />
      <SecTwo />
      <SecThree />
      <DivCom />
      <SeC4 />
      <DivCom />
      <SeC5 />
      <SeC6 />
      <SeC7 />
    </main>
</div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue'
import SecOne from './components/SecOne.vue'
import SecTwo from './components/SecTwo.vue'
import SecThree from './components/SecThree.vue'
import DivCom from './components/DivCom.vue'
import SeC4 from './components/SeC4.vue'
import SeC5 from './components/SeC5.vue'
import SeC6 from './components/SeC6.vue'
import SeC7 from './components/SeC7.vue'

export default {
  components: {
    HeaderComp,
    SecOne,
    SecTwo,
    SecThree,
    DivCom,
    SeC4,
    SeC5,
    SeC6,
    SeC7
   },
}

</script>

<style lang="scss">
*{padding: 0;
  margin: 0;
  box-sizing: border-box}

  div{
    font-family: Arial, Helvetica, sans-serif;
  }

// NOTE come si può inserire uno style dentro l'altro?
// NOTE come si può stampare gli elementi di un arrow ?
// NOTE capire come dimicizzare le immagine sella SecThree
</style>
