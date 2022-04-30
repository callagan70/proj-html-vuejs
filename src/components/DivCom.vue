<template>
    <div id="divisore">
<!-- FIXME inserire una icona della freccia -->
        <div><a href="#">READ OUR BLOG -></a></div>
    </div>
</template>

<script>
export default {
    name: 'DivCom',
     
}

</script>

<style scoped lang="scss">

#divisore{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: black;
    width: 100%;
    height: 100px;
}

#divisore>div a{
    text-decoration: none;
    color: white;
    font-weight: 700;
}


</style>