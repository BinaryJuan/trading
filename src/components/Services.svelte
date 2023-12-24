<section id="services" class="servicesContainer">
    <h3>SERVICES</h3>
    <div class="servicesList">
        <div class="serviceBox">
            <img src="/services/traders.svg" alt="traders" />
            <h4>Traders</h4>
        </div>
        <div class="serviceBox">
            <img src="/services/forwarder.svg" alt="forwarding" />
            <h4>Forwarder</h4>
        </div>
        <div class="serviceBox">
            <img src="/services/shipping.svg" alt="shipping" />
            <h4>Shipping</h4>
        </div>
        <div class="serviceBox">
            <img src="/services/warehousing.svg" alt="warehousing" />
            <h4>Warehousing</h4>
        </div>
        <div class="serviceBox">
            <img src="/services/products.svg" alt="products" />
            <h4>Products</h4>
        </div>
    </div>
</section>

<style>
    .servicesContainer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 60px 0;
        margin-bottom: 100px;
    }

    .servicesContainer h3 {
        font-size: 3rem;
        letter-spacing: 10px;
    }

    .servicesList {
        margin-top: 40px;
        width: 100%;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        flex-wrap: wrap;
        row-gap: 40px;
        column-gap: 40px;
    }

    .serviceBox {
        width: 250px;
        height: 250px;
        background-color: #f1f1f1;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        border-radius: 1rem;
    }

    .serviceBox img {
        width: 6rem;
        transition: all.5s;
        margin-bottom: 4px;
    }

    .serviceBox h4 {
        font-weight: normal;
        font-size: 1.3rem;
    }

    .serviceBox:hover img {
        transform: scale(1.1, 1.1);
        transition: all .5s;
    }
</style>