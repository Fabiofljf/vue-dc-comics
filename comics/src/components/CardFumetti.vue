<template>
    <div class="card">
        <img :src="img" alt="title">
        <h6 class="text-light">{{title}}</h6>
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
