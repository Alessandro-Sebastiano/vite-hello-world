<script>

export default {

    name: 'AppTitle',

    data() {

        return {

            title: 'La mia prima app con Vite!',

        }

    }

}

</script>



<template>

    <div class="title">

        <h1>{{ title }}</h1>

    </div>

</template>


<style lang="css">
.title {
    text-align: center;
    padding: 4px;
}
</style>