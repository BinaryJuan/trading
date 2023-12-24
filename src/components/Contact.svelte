<section id="contact" class="contactContainer">
    <h3>CONTACT</h3>
    <div class="contactOptions">
        <div class="contactOption">
            <a href="href=https://wa.me/+11111111111" target='_blank' rel="noreferrer"><img src="/contact/whatsapp.svg" alt="whatsapp" /></a>
            <p>+1 111 111 1111</p>
        </div>
        <div class="contactOption">
            <a href="mailto:example@outlook.com" target='_blank' rel="noreferrer"><img src="/contact/envelope.svg" alt="email" /></a>
            <p>example@outlook.com</p>
        </div>
    </div>
</section>

<style>
    .contactContainer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 60px 0;
        margin-bottom: 60px;
    }

    .contactContainer h3 {
        font-size: 3rem;
        letter-spacing: 10px;
    }

    .contactOptions {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        flex-wrap: wrap;
        margin-top: 80px;
        width: 70%;
        row-gap: 50px;
    }

    .contactOption {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        width: 400px;
        height: 400px;
        background-color: #f0f0f0;
        border-radius: 1rem;
    }

    .contactOption img {
        margin-bottom: 30px;
    }

    .contactOption p {
        font-size: 1.3rem;
    }
</style>