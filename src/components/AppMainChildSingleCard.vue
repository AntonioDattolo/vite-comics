<script>
export default{
    name:"SingleComic",
    props: ["thisComic"],
    data(){

    }
}
</script>

<template>
    <div  class="col-12 col-md-4 col-lg-2 bg-transparent">
        <img :src="thisComic.thumb" class="card-img-top p-3" alt="...">
        <p class="card-text text-white px-2">{{ thisComic.series }}</p>
    </div>
</template>
<style scoped>
img{
    aspect-ratio: 1;
    object-fit: cover;
    object-position: top;
}
</style>