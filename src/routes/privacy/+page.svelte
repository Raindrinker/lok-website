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

        <div class="content2">
            <div class="text">
                <b style="font-size: 32px">Privacy Policy</b>

                <br><br>
                <b style="font-size: 24px">Data Collection</b>
                <br><br>
                We do not collect, process or store any personal data from our games.
                <br><br>
                On iOS and Android, our games collect non-personal data using integrated Apple and Google services for leaderboards, achievements, and cloud saves such as Apple iCloud, GameCenter, and Google Play Games Services. Such data is stored by Apple and Google. We do not store personal or gameplay data on our servers. These services have their own privacy policies.
                <br><br>
                We don't place any advertisements in our games.
                <br><br>
                <b style="font-size: 24px">Contacting Us</b>
                <br><br>
                LOK Digital is published by Draknek.
                <br><br>
                If you have any questions about this Privacy Policy, please <a href="mailto:hello@lok-digital.com" class="link">contact us</a>.

            </div>
        </div>
    </div>


</div>

<script>
    import logo from '$lib/images/lok-digital/logo.png';
    import book from '$lib/images/book.png';
    import credits from '$lib/images/lok-digital/credits.png';
    import credits2 from '$lib/images/lok-digital/DraknekFriendsLogo.png';
    import steam_logo from '$lib/images/steam.png';
    import decoration1 from '$lib/images/lok-digital/decoration1.png';
    import decoration2 from '$lib/images/lok-digital/decoration2.png';

    import gif1 from "$lib/images/lok-digital/gif1.gif";
    import gif2 from "$lib/images/lok-digital/gif2.gif";
    import gif3 from "$lib/images/lok-digital/gif3.gif";
    import gif4 from "$lib/images/lok-digital/gif4.gif";
</script>

<style>

    .link {
        text-decoration: underline !important;
    }

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
        max-width: 80%;
        position: relative;
    }

    .content2 {
        padding: 64px;

        background-color: white;
        margin-bottom: 128px;

        -webkit-box-shadow: 0px 3px 9px 2px rgba(0,0,0,0.4);
        box-shadow: 0px 3px 9px 2px rgba(0,0,0,0.4);
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

        max-width: 800px;

        text-align: justify;

        font-size: 1.15em;

        color: #333333;
    }

    .credits-img {
        max-width: 200px;
    }

    .images {
        max-width: 800px;
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
    }

    @media (max-width: 1250px) {
        .content {
            max-width: 85%;
        }
        .text {

            font-size: 1em;
        }

        .footer {
            flex-direction: column;
        }

        .images {
            flex-direction: column;
        }

        .image-box {
            max-width: 100%;
            display: flex;
            flex-shrink: 1;
        }

        .text.list {
            margin-left: -16px;
        }

        .decor1 {
            visibility: hidden;
        }

        .decor2 {
            visibility: hidden;
        }
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

</style>