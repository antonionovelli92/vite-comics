<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            links: [
                { text: 'Characters', url: '#', current: false },
                { text: 'Comics', url: '#', current: true },
                { text: 'Movies', url: '#', current: false },
                { text: 'TV', url: '#', current: false },
                { text: 'Games', url: '#', current: false },
                { text: 'Collectibles', url: '#', current: false },
                { text: 'Videos', url: '#', current: false },
                { text: 'Fans', url: '#', current: false },
                { text: 'News', url: '#', current: false },
                { text: 'Shop', url: '#', current: false }
            ]
        }
    },

}

</script>

<template>

    <header class="container">
        <figure class="nav-logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </figure>
        <ul class="nav-links">
            <li v-for="link in links" :key="link.text">
                <a :href="link.url" :class="{ 'active': link.current }">{{ link.text }}</a>
            </li>
        </ul>
    </header>


</template>


<style lang="scss">
img {
    max-width: 100%;
    height: 75px;
}

header {
    width: 100%;
    height: 80px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 1.25rem 0;

    .nav-links {
        display: flex;
        flex-direction: row;
        justify-content: flex-end;
        padding: 0;

        li {
            list-style: none;

            a {
                display: inline-block;
                text-decoration: none;
                color: #524647;
                text-transform: uppercase;
                margin: 0 0.75rem;


            }
        }
    }
}
</style>