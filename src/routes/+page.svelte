<div class="about">
    <div class="content">

        <div class="decor1">
            <img src={decoration1}/>
        </div>
        <div class="decor2">
            <img src={decoration2}/>
        </div>

        <div class="logo-img-div">

            <img src={logo} class="logo-img"/>


        </div>


        <div class="laurels laurels-pc">

            <img src={laurel7} class="laurel"/>
            <img src={laurel1} class="laurel"/>
            <img src={laurel3} class="laurel"/>
            <img src={laurel4} class="laurel"/>

        </div>

        <div class="laurels laurels-pc">
        <img src={laurel5} class="laurel"/>
        <img src={laurel6} class="laurel"/>
        <img src={laurel8} class="laurel"/>
            <img src={laurel2} class="laurel"/>
            </div>

        <div class="laurels laurels-pc">
            <img src={laurel9} class="laurel"/>
        </div>

        <div class="laurels laurels-mobile">

            <img src={laurel7} class="laurel"/>
            <img src={laurel1} class="laurel"/>

        </div>

        <div class="laurels laurels-mobile">

            <img src={laurel3} class="laurel"/>
            <img src={laurel4} class="laurel"/>

        </div>

        <div class="laurels laurels-mobile">

            <img src={laurel5} class="laurel"/>
            <img src={laurel6} class="laurel"/>

        </div>

        <div class="laurels laurels-mobile">

            <img src={laurel8} class="laurel"/>
            <img src={laurel2} class="laurel"/>

        </div>

        <div class="laurels laurels-mobile">

            <img src={laurel9} class="laurel"/>

        </div>


        <div class="content2">
            <div class="content-top">
                <div class="tagline">Learn world-changing words and master their mind-bending effects.</div>

                <div class="div-video">
                    <div class="video">
                        <iframe class="video-iframe"
                                src="https://www.youtube.com/embed/ofCYQGRWcS4?rel=0&modestbranding=1&autohide=1">
                        </iframe>
                    </div>
                </div>

                <div class="steam-embed-pc">
                    <iframe src="https://store.steampowered.com/widget/2207440/" frameborder="0" width="646" height="190"></iframe>
                </div>



                <a href="https://store.steampowered.com/app/2207440/LOK_Digital/" target="_blank">
                    <div class="steam-embed-mobile">
                        <img src={steam_logo} class="steam-img"/>
                        <u>LOK Digital on Steam</u>
                    </div>
                </a>

                <a href="https://draknek.itch.io/lok-digital" target="_blank">
                    <div class="itch-embed-mobile">
                        <img src={itch_logo} class="steam-img"/>
                        <u>LOK Digital on itch.io</u>
                    </div>
                </a>

                <div class="itch-widget">
                <iframe frameborder="0" src="https://itch.io/embed/3136851" width="552" height="167"><a href="https://draknek.itch.io/lok-digital">LOK Digital by Draknek &amp; Friends, Letibus Design, IcedropGames</a></iframe>
                </div>

                <div class="mobile-links">
                <a href="https://play.google.com/store/apps/details?id=com.IcedropGames.LOK" target="_blank">
                    <div class="android-embed">
                        <img src={android_logo} class="steam-img"/>
                        <u>Android</u>
                    </div>
                </a>

                    <div class="h-sep"></div>

                <a href="https://apps.apple.com/app/id6476513210" target="_blank">
                    <div class="ios-embed">
                        <img src={ios_logo} class="steam-img"/>
                        <u>iOS</u>
                    </div>
                </a>
                </div>

                <form action="https://secure.draknek.org/sendy/subscribe" method="POST" accept-charset="utf-8" class="mailing-form">
                    <input type="email" name="email" id="email" class="email" placeholder="email address" required />
                    <div style="position: absolute; left: -5000px;">
                        <label for="hp">HP</label><br/>
                        <input type="text" name="hp" id="hp"/>
                    </div>
                    <input type="hidden" name="list" value="hJp8h763x9G9E8Ujj43DTVwA"/>
                    <input type="hidden" name="subform" value="yes"/>
                    <input type="submit" name="submit" id="submit" class="button-primary" value="Subscribe to updates"/>
                </form>
            </div>




            <div class="separator">
                <img src={lokites2} class="separator-lokites2"/>
            </div>

            <div class="links">
                <a href="/presskit">
                    <div class="presskit-link">
                        PRESSKIT >
                    </div>
                </a>

                <a href="mailto:hello@lok-digital.com">
                    <div class="contact-link">
                        CONTACT US >
                    </div>
                </a>
            </div>



            <div class="credits-middle">
                <div class="credit1">
                    <a href="https://www.draknek.org/">
                        <div>
                            Publishing
                        </div>
                        <div class="credits-middle-img-div">
                            <img src={credits2} class="credits-middle-img"/>
                        </div>
                    </a>
                </div>
                <div class="credit2">
                    <a href="https://www.blazgracar.com/letibus">
                        <div>
                            Design
                        </div>
                        <div class="credits-middle-img-div">
                            <img src={credits_letibus} class="credits-middle-img"/>
                        </div>
                    </a>
                </div>
                <div class="credit3">
                    <a href="https://www.icedropgames.com/">
                        <div>
                            Development
                        </div>
                        <div class="credits-middle-img-div">
                            <img src={credits_icedrop} class="credits-middle-img"/>
                        </div>

                    </a>
                </div>
            </div>

            <div class="separator">
                <img src={lokites1} class="separator-lokites1"/>
            </div>


            <div class="book-duet">
                <img src={book} class="book-img"/>
                <div class="book-duet-text">
                    An adaptation of the acclaimed pen & paper puzzle book LOK
                    <a href="https://www.blazgracar.com/lok">
                        <div class="book-link">
                            ABOUT THE BOOK >
                        </div>
                    </a>
                </div>

            </div>

            <div class="separator separator-3">
                <img src={lokites3} class="separator-lokites2"/>
            </div>




        </div>
    </div>


</div>

<svelte:head>
    <style>
        #header {
            display: none;
        }
    </style>
</svelte:head>

<script>
    import logo from '$lib/images/lok-digital/logo.png';
    import book from '$lib/images/book.png';
    import credits_icedrop from '$lib/images/lok-digital/credits_icedrop.png';
    import credits_letibus from '$lib/images/lok-digital/credits_letibus.png';
    import credits2 from '$lib/images/lok-digital/DF_OutlineCutout.svg';
    import steam_logo from '$lib/images/steam.png';
    import android_logo from '$lib/images/android.png';
    import ios_logo from '$lib/images/apple.png';
    import itch_logo from '$lib/images/itchio.png';
    import decoration1 from '$lib/images/lok-digital/decoration1.png';
    import decoration2 from '$lib/images/lok-digital/decoration2.png';

    import lokites1 from '$lib/images/Figures1.jpg';
    import lokites2 from '$lib/images/Figures2.jpg';
    import lokites3 from '$lib/images/Figures3.jpg';

    import laurel1 from '$lib/laurels-thinky-awards-2024.svg';
    import laurel2 from '$lib/laurels-wasd-curios-2024.svg';
    import laurel3 from '$lib/laurels-develop-2024.png';
    import laurel4 from '$lib/laurels-PCGaming-2024.png';
    import laurel5 from '$lib/laurels-indie-game-contest.png';
    import laurel6 from '$lib/laurels-future-play.png';
    import laurel7 from '$lib/laurels-dotd.png';
    import laurel8 from '$lib/laurels-playtopia.png';
    import laurel9 from '$lib/laurels-igf.png';

</script>

<style>

    .about {
        display: flex;
        flex-direction: column;
        align-items: center;

        width: 100%;

        font-family: CenturyLocal;

        background: #EEEEEE url("/images/lok-bg.jpeg");
        background-size: 600px;

        position: relative;
    }

    .content {
        position: relative;
        align-items: center;
        justify-content: center;
        display: flex;
        flex-direction: column;
    }

    .content2 {

        background-color: white;

        -webkit-box-shadow: 0px 3px 9px 2px rgba(0,0,0,0.4);
        box-shadow: 0px 3px 9px 2px rgba(0,0,0,0.4);
        align-items: center;
        justify-content: center;

        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .logo-img-div {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .logo-img {
        max-width: 400px;
    }

    .text {

        text-align: justify;

        font-size: 1.15em;

        color: #333333;
    }

    .credits-img {
        max-width: 200px;
    }

    .images {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        align-content: stretch;
        padding-top: 32px;
        padding-bottom: 32px;
    }

    .image-box {
        max-width: 50%;
        display: flex;
    }

    .image-box-pad {
        padding: 8px;
        padding-bottom: 0px;
        padding-top: 6px;
        width: 100%;
    }

    .screenshot-img {
        border: 4px solid black;
        flex-shrink: 1;
        width: 100%;
    }

    .footer {
        display: flex;
        padding-left: 32px;
        padding-right: 16px;
        padding-bottom: 16px;
    }

    .footer-img {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-grow: 0;
    }
    .empty {
        flex-grow: 1;
        min-width: 64px;
    }

    @media (max-width: 1250px) {
        .content {
            max-width: 90%;
            position: relative;
            padding: 0 !important;
        }
        .text {

            font-size: 1em;
        }

        .footer {
            flex-direction: column;
        }

        .video {
            max-width: 80vw;
        }

        .video-iframe {
        }

        .content2 {
            max-width: 85% !important;
        }

        .book-duet {
            flex-direction: column !important;
        }

        .credits-middle {
            column-gap: 4px !important;
        }

    }

    @media (max-width: 900px) {
        .steam-embed-pc {
            display: none;
        }

        .itch-widget {
            display: none;
        }

        .steam-embed-mobile, .itch-embed-mobile {
            display: flex !important;
        }

        .content {
            max-width: 100% !important;
        }

        .content2 {
            max-width: 100% !important;
        }

        .links {
            flex-direction: column;

        }

        .contact-link {
            padding-bottom: 32px;
        }

        .button-primary {
            font-size: 1em !important;
            padding: 4px !important;
        }

        .email {
            font-size: 1em !important;
        }

        .credits-middle {
            flex-direction: column;
        }

        .laurels {
            flex-direction: column;
        }

        .laurels-mobile {
            display: flex !important;
        }

        .laurels-pc {
            display: none !important;
        }
    }

    .laurels-pc {
        padding-bottom: 32px;
    }

    .decor1 {
        position: absolute;
        top: 250px;
        left: -500px;
        scale: 1;
    }

    .decor2 {
        position: absolute;
        top: 1000px;
        right: -550px;
        scale: 1;
    }

    .tagline {
        font-size: 1.5em;
        font-weight: bold;
        padding-bottom: 64px;
    }

    .div-video {
        padding-bottom: 64px;
        position: relative;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .video {
        position: relative;
        padding-bottom: 56%;
        width: 100%;
        text-align: left;
        max-width: 646px;
    }

    .video-iframe {
        width: 100%;
        position: absolute;
        height: 100%;
        overflow: hidden;
    }

    .content2-blurb {
        padding-top: 16px;
        padding-bottom: 16px;
        text-align: left;
        text-align: justify;

        font-size: 1.15em;

        color: #333333;
        display: none;
    }

    .steam-embed {
        padding-bottom: 64px;
    }

    .presskit-link {
        font-family: CenturyLocal;
        font-weight: bold;
        font-size: 2em;
        margin-top: 16px;
        margin-bottom: 16px;
    }

    .contact-link {
        font-family: CenturyLocal;
        font-weight: bold;
        font-size: 2em;
        margin-top: 16px;
        margin-bottom:16px;
    }

    .steam-img {
        max-width: 64px;
    }

    .steam-embed-mobile, .ios-embed, .android-embed, .itch-embed-mobile {
        font-weight: bold;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 16px;
        margin-bottom: 32px;
        display: none;
    }

    .steam-embed-pc {
        margin-bottom: 64px;
    }

    .book-img {
        max-width: 300px;
    }

    .book-duet {
        display: flex;
        align-items: center;
        padding-bottom: 32px;
    }

    .book-duet-text {
        font-size: 1.2em;
        max-width: 400px;
        padding-top: 64px;
    }

    .book-link {
        font-family: CenturyLocal;
        font-weight: bold;
        font-size: 1.2em;
        margin-top: 16px;
        margin-bottom: 64px;
    }

    .button-primary {
        background-color: black;
        color: white;
        border-radius: 8px;
        cursor: pointer;
    }

    .button-primary:hover {
        background-color: #333333;
    }

    .separator {
        width: 100%;
        height: 16px;
        background-color: black;
        margin-bottom: 32px;
        margin-top: 32px;
        position: relative;
    }

    .content-top {
        padding: 64px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        max-width: 100%;
    }

    .credits-middle {
        display: flex;
        width: 100%;
        align-items: center;
        justify-content: center;
        font-size: 1.2em;
        padding-bottom: 64px;
        padding-top: 32px;
        row-gap: 32px;
        column-gap: 64px;
        font-weight: bold;
    }

    .credits-middle-img-div {
        height: 150px;
        width: 200px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .credits-middle-img {
        max-width: 100%;
        max-height: 100%;
    }

    .separator-lokites1 {
        position: relative;
        height: 32px;
        bottom: 32px;
        left: 64px;
        float: left;
    }

    .separator-lokites2 {
        position: relative;
        height: 32px;
        bottom: 32px;
        right: 64px;
        float: right;
    }

    .separator-3 {
        margin-bottom:  0;
    }


    .links {
        display: flex;
        column-gap: 64px;
        row-gap: 64px;
    }

    .button-primary {
        font-family: CenturyLocal;
        font-size: 1.2em;
        padding: 4px 16px;

        border: 0px;
        max-width: 80%;
        margin-top: 4px;
    }

    .email {
        font-family: CenturyLocal;
        font-size: 1.2em;
        max-width: 80%;
    }

    .laurels {
        display: flex;
    }

    .laurel {
        max-width: 200px;
    }

    .laurels-mobile {
        display: none;
        flex-direction: row;
        padding-bottom: 32px;
        column-gap: 16px;
    }

    .laurels-mobile .laurel {
        max-width: 160px;
    }

    .itch-widget {
        margin-bottom: 32px;
    }

    .android-embed {
        display: flex !important;
    }

    .ios-embed {
        display: flex !important;
    }

    .mailing-form {
        margin-top:  32px;
    }

    .mobile-links {
        display: flex;
        flex-direction: row;
    }

    .h-sep {
        width: 42px;
    }

</style>