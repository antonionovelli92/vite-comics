<script>
export default {
    name: 'AppMain',
    data() {
        return {

        }
    },

}

</script>

<template>
    <main>
        <section class="section-black">
            <h2> --> Content goese here! </h2>
        </section>
        <section class="section-blu"></section>
    </main>

</template>


<style lang="scss">
.section-black {
    width: 100%;
    height: 120px;
    background-color: #1C1C1C;

    h2 {
        display: flex;
        margin: 1.25rem 0;
        color: white;
        height: 100%;
        align-items: center;
    }
}

.section-blu {
    width: 100%;
    height: 140px;
    background-color: #0382F9;

}
</style>