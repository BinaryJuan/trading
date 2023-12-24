<nav class="navContainer">
    <div class="navFlexLogo">
        <img src="/logo.png" alt="logo" />
        <h2>NAMENAME</h2>
    </div>
    <div class="navFlexMenu">
        <ul>
            <li><a href="/#home">HOME</a></li>
            <li>
                <div class="servicesDisplay">
                    <a href="/#services">SERVICES</a>
                    <div class="navServices">
                        <ul>
                            <li><a href="/#services">TRADERS</a></li>
                            <li><a href="/#services">FORWARDER</a></li>
                            <li><a href="/#services">SHIPPING</a></li>
                            <li><a href="/#services">WAREHOUSING</a></li>
                            <li><a href="/#services">PRODUCTS</a></li>
                        </ul>
                    </div>
                </div>
            </li>
            <li><a href="/#brands">BRANDS</a></li>
            <li><a href="/#contact">CONTACT</a></li>
        </ul>
        <button>
            <img src="/language/eng.png" alt="language" />
        </button>
    </div>

</nav>

<style>
    .navContainer {
        height: 60px;
        width: 100%;
        background-color: #232536;
        color: #FFFFFF;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .navServices {
        position: relative;
        opacity: 0;
        visibility: hidden;
        transition: all .5s;
        z-index: 99;
    }

    .navServices ul {
        position: absolute;
        list-style: none;
        margin: 0;
        padding: 10px 20px;
        top: 1rem;
        flex-direction: column !important;
        background-color: #232536;
        font-size: 1rem !important;
        border-end-start-radius: 1rem;
        border-end-end-radius: 1rem;
        z-index: 99;
    }

    .servicesDisplay:hover .navServices {
        opacity: 1;
        transition: all .5s;
        visibility: visible;
    }

    .navFlexLogo {
        display: flex;
        align-items: center;
        gap: 15px;
        padding-left: 3%;
        user-select: none;
    }

    .navFlexLogo img {
        width: 50px;
    }

    .navFlexLogo h2 {
        font-weight: normal;
    }

    .navFlexMenu {
        display: flex;
        gap: 40px;
        align-items: center;
    }

    .navFlexMenu ul {
        display: flex;
        list-style: none;
        gap: 20px;
        margin-left: -12%;
        font-weight: lighter;
        font-size: 18px;
    }

    .navFlexMenu li {
        border-left: 2px solid transparent;
        border-radius: .05rem;
        padding-left: 6px;
        transition: border .6s;
        position: relative;
    }

    .navFlexMenu li:hover {
        border-left: 2px solid #ddefff;
        transition: border .8s;
    }

    .navFlexMenu ul li a {
        color: #FFFFFF;
        text-decoration: none;
        cursor: pointer;
    }

    .navFlexMenu button {
        cursor: pointer;
        background: none;
        color: inherit;
        border: none;
        padding: 0;
        font: inherit;
        cursor: pointer;
        outline: inherit;
    }

    .navFlexMenu button img {
        width: 45px;
    }
</style>