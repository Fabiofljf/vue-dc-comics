<template>
    <div class="card">
        <img :src="img" alt="title">
        <h5 class="text-light">{{title}}</h5>
    </div>
</template>

<script>

export default({
    name: 'CardFumetti',
    props: {
        img: String,
        title: String,
    },
})
</script>

<style lang="less" scoped>

</style>