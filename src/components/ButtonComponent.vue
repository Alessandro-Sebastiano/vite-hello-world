<script>

export default {

    name: 'ButtonComponent',

    data() {

        return {


        }

    }

}

</script>



<template>

    <div class="button">

        <span>Click</span>

    </div>

</template>


<style lang="css">
.button {
    padding: 9px 26px;
    font-weight: 600;
    color: #fff;
    background-color: blue;
    display: inline-block;
    border-radius: 8px;
    cursor: pointer;
    transition: all 0.2s ease-out;
}

.button:hover {
    background-color: blueviolet;
}
</style>