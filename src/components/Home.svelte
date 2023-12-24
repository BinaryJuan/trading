<script>
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    import '@splidejs/svelte-splide/css';
    const options = {
        rewind  : true,
        autoplay: true
    }
</script>

<section id="home">
    <Splide aria-label="Trade" options={options}>
        <SplideSlide>
            <div class="carouselBlock">
                <div class="imageText textLeft">
                    <h2>EFFICIENCY</h2>
                    <p>You ask, we deliver.</p>
                </div>
                <img src="/carousel/carousel1.png" alt="carousel1"/>
            </div>
        </SplideSlide>
        <SplideSlide>
            <div class="carouselBlock">
                <div class="imageText textRight">
                    <h2>TRUST</h2>
                    <p>With us, you can take a break</p>
                </div>
                <img src="/carousel/carousel2.png" alt="carousel2"/>
            </div>
        </SplideSlide>
        <SplideSlide>
            <div class="carouselBlock">
                <div class="imageText textLeft">
                    <h2>VARIETY</h2>
                    <p>We work with a wide variety of products</p>
                </div>
                <img src="/carousel/carousel3.png" alt="carousel3"/>
            </div>
        </SplideSlide>
    </Splide>
</section>

<style>
    .carouselBlock {
        position: relative;
    }

    .imageText {
        position: absolute;
        color: #FFFFFF;
    }

    .imageText h2 {
        font-size: 6rem;
    }

    .imageText p {
        font-weight: lighter;
        font-size: 1.5rem;
        color: #C7C7C7;
        padding-left: 6px;
    }

    .textLeft {
        left: 10%;
        top: 8rem;
    }

    .textRight {
        right: 10%;
        top: 8rem;
    }
</style>