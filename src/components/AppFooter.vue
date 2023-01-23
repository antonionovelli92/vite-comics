<script>
export default {
    name: 'AppFooter',
    data() {
        return {

        }
    },

}

</script>

<template>
    <footer>
        <section class="footer-bg">
            <div class="container d-flex">
                <div class="footer-bg-lists ">
                    <ul>
                        <h4>DC COMICS</h4>
                        <li>
                            <a href="">Characters</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Movies</a>
                        </li>
                        <li>
                            <a href="">TV</a>
                        </li>
                        <li>
                            <a href="">Games</a>
                        </li>
                        <li>
                            <a href="">Videos</a>
                        </li>
                        <li>
                            <a href="">News</a>
                        </li>
                        <h4>TITLE</h4>
                        <li>
                            <a href="">SHOP</a>
                        </li>
                        <li>
                            <a href="">Shop DC</a>
                        </li>
                        <li>
                            <a href="">Shop DC Collectibles</a>
                        </li>
                    </ul>
                    <ul>
                        <h4>DC</h4>
                        <li>
                            <a href="">Terms Of Use</a>
                        </li>
                        <li>
                            <a href="">Privacy Policy (New)</a>
                        </li>
                        <li>
                            <a href="">Ad Choices</a>
                        </li>
                        <li>
                            <a href="">Advertising</a>
                        </li>
                        <li>
                            <a href="">Jobs</a>
                        </li>
                        <li>
                            <a href="">Subscriptions</a>
                        </li>
                        <li>
                            <a href="">Talen Workshops</a>
                        </li>
                        <li>
                            <a href="">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="">Ratings</a>
                        </li>
                        <li>
                            <a href="">Shop Helps</a>
                        </li>
                        <li>
                            <a href="">Contact Us</a>
                        </li>

                    </ul>
                    <ul>
                        <h4>SITES</h4>
                        <li>
                            <a href="">DC</a>
                        </li>
                        <li>
                            <a href="">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="">DC Kids</a>
                        </li>
                        <li>
                            <a href="">DC Universe</a>
                        </li>
                        <li>
                            <a href="">DC Power Visa</a>
                        </li>

                    </ul>
                </div>
                <div class="footer-bg-logo">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </section>
        <section class="footer-follow">
            <div class="container d-flex">
                <div class="footer-btn">
                    <button>SIGN UP NOW!</button>
                </div>
                <div class="footer-icons">
                    <ul>
                        <h4>FOLLOW US</h4>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-facebook.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-youtube.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-twitter.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-pinterest.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <img src="../assets/img/footer-periscope.png" alt="">
                            </a>
                        </li>
                    </ul>
                </div>
            </div>

        </section>

    </footer>

</template>


<style lang="scss">
footer {
    width: 100%;
    min-height: 600px;

    .footer-bg {
        height: 500px;
        background-image: url('../assets/img/footer-bg.jpg');

        .d-flex {
            display: flex;
            justify-content: space-between;
        }

        .footer-bg-lists {
            display: flex;

            ul {
                color: white;
                margin-right: 5rem;

                h4 {
                    margin: 1rem 0;
                    font-size: 24px;
                }

                li {
                    list-style: none;
                    margin: 0.25rem 0;

                    a {
                        text-decoration: none;
                        color: #869586;

                    }
                }
            }


        }

        .footer-bg-logo {
            img {
                width: 800px;
                height: 498px;
            }
        }
    }


    .footer-follow {
        min-height: 100px;
        background-color: #303030;
        display: flex;
        justify-content: space-between;

        .d-flex {
            display: flex;
            justify-content: space-between;
            width: 100%;
            align-items: center;
        }

        button {
            padding: 20px 40px;
            border: 3px solid #0382F9;
            background-color: #303030;
            color: white;
            font-size: 22px;
            cursor: pointer;
        }

        ul {
            display: flex;
            flex-direction: row;
            align-items: center;

            h4 {
                color: #0382F9;
                font-size: 25px;
                margin-right: 2rem;
            }

            li {
                list-style: none;

                img {
                    max-width: 100%;
                    height: 35px;
                    margin: 0 0.5rem;

                }

            }

        }
    }
}
</style>