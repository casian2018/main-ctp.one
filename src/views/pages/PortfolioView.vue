<template>
    <section class="portfolio section" id="portfolio">
        <h2 class="section__title">Portofolio</h2>
        <span class="section__subtitle">Most recent work</span>

        <div class="portofolio__container container swiper">
            <div class="swiper-wrapper">
                <!--==================== PORTFOLIO 1 ====================-->
                <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/BookNook.png" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">Book Nook</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with animated interactions.
                        </p>
                        <a href="https://booknook.ctp.one" class="button button--flex button--small portofolio__button">
                            View
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div>

                <!--==================== PORTFOLIO 2 ====================-->
                <div class="portofolio__content grid swiper-slide">
                    <img src="frontend/assets/img/BookNook.png" alt="" class="portofolio__img">

                    <div class="portofolio__data">
                        <h3 class="portofolio__title">Shoe Kingz</h3>
                        <p class="portofolio__description">Website adaptable to all devices, with animated interactions, but no working buttons.
                        </p>
                        <a href="https://shoekingz.ctp.one" class="button button--flex button--small portofolio__button">
                            View
                            <i class="uil uil-arrow-right button__icon"></i>
                        </a>
                    </div>
                </div>
            <!-- add arrows -->
            <div class="swiper-button-next">
                <i class="uil uil-angle-right-b swiper-portofolio-icon"></i>
            </div>
            <div class="swiper-button-prev">
                <i class="uil uil-angle-left-b swiper-portofolio-icon"></i>
            </div>

            <!-- add pagination -->
            <div class="swiper-pagination"></div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Portfolio'
}
</script>