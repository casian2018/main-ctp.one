<template>
    <section class="home section" id="home">
        <div class="home__container container grid">
            <div class="home__content grid">
                <div class="home__social">
                    <a href="https://github.com/casian2018" class="home__social-icon" target="_blank">
                        <i class="uil uil-github-alt"></i>
                    </a>
                </div>

                <div class="home__img">
                   <img src="frontend/assets/img/Screenshot_20230128_210624_Gallery.jpg" alt="" class="about__img">                          
                </div>

                <div class="home__data">
                    <h1 class="home__title">Hi, I'am Casian The Programmer</h1>
                    <h3 class="home__subtitle"> Website Developer && Foto/Video Creator</h3>
                    <p class="home__description">High level experience in web design and development knowledge, producing quality work.
                    </p>
                    <a href="#contact" class="button button--flex">
                        Contact Me <i class="uil uil-message button__icon"></i>
                    </a>
                </div>
            </div>

            <div class="home__scroll">
                <a href="#about" class="home__scroll-button button--flex">
                    <i class="uil uil-mouse-alt home__scroll-mouse"></i>
                    <span class="home__scroll-name">Scroll down</span>
                    <i class="uil uil-arrow-down home__scroll-arrow"></i>
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Home'
};
</script>