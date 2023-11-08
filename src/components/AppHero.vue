<template>
    <main>
        <div class="outer-container">
            <div v-for="number in 9" class="img-container">
                <img :src="'/img/cianfry-'+number+'.jpg'" alt="" srcset="">
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name: 'AppHero',
    data () {
        return {
            titolo: 'jumbotron',
            
        }
    },
    
}
</script>

<style lang="css" scoped >
    .img-container{
        width: calc(100%/9);
    }
    img{
        max-width: 100%;
    }

    .outer-container{
        justify-content: center;
        width: 100vw;
        max-width: 100%;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }
    main{
        padding: 20px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        overflow-x: hidden;
    }
</style>
