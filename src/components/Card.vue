<template>
    <div>
        <div>
            <img :src="ruta" alt="">
        </div>
    </div>
</template>
<script>
    export default {
        name: 'Card',
        props: {
            ruta: String
        }
    }
</script>

<style scoped>
    img{
        border-radius: 25.4699px;
    }
</style>