<script>

import ButtonComponent from './ButtonComponent.vue';

export default {

    components: {
        ButtonComponent,
    },

    name: 'AppHero',

    data() {

        return {

            jumboTitle: 'Custom Jumbotron'

        }

    }

}

</script>



<template>

    <div class="jumbotron">
        <h2>{{ jumboTitle }}</h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Placeat maiores, quas et officiis nulla libero
            quibusdam vel ab consectetur nostrum rem corporis optio dolorem voluptatem dignissimos sint, quaerat iure
            impedit.
        </p>
        <ButtonComponent />
    </div>

</template>


<style lang="css">
.jumbotron {
    width: 80%;
    padding: 32px 24px;
    background-color: lightgray;
    min-height: 80px;
    margin-top: 32px;
}

.jumbotron h2 {
    margin-bottom: 14px;
}

.jumbotron p {
    padding: 12px 0;
    border-bottom: 1px solid grey;
    margin-bottom: 18px;
}
</style>