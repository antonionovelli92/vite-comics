<script>
export default {
    name: 'BuildComic',
    props: {
        comic: Object,
    }
};
</script>


<template>
    <div class="comic-card">
        <img :src="comic.thumb" :alt="comic.series">
        <h4>{{ comic.series }}</h4>
    </div>
</template>
<style scoped lang="scss">
.comic-card {
    margin: 1rem 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;


    img {
        width: 180px;
        height: 150px;
        object-fit: fill;

    }

    h4 {
        color: white;
        text-align: left;
        margin: 0.5rem 0;

    }
}
</style>