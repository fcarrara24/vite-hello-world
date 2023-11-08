<template>
    <main>
        <h2 class="heroStyle">{{ titolo }}</h2>
    </main>
</template>

<script>
export default {
    name: 'AppHero',
    setup () {
        return {
            titolo: 'jumbotron'
        }
    }
}
</script>

<style lang="css" scoped >

</style>
