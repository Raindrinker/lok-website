<div class="about">
    <div class="content">

        <div class="logo-img-div" bind:this={element}>
            <img src={logo} class="logo-img"/>
        </div>

        <div class="content2">
            <div class="presskit">
                <div class="column1">
                    <img src={lok_steam}/>

                    <div class="presskit-title2 pt">By Draknek&Friends</div>

                </div>
                <div class="column2">
                    <div class="presskit-title1 pt pb">Factsheet</div>
                    <div class="presskit-title2">Developer</div>
                    <div class="presskit-text">Letibus Designs<br>Icedrop Games</div>
                    <div class="presskit-title2 pt">Publisher</div>
                    <div class="presskit-text">Draknek & Friends</div>
                    <!--<div class="presskit-title2 pt">Platforms</div>
                    <div class="presskit-text">Steam<br>Android<br>IOs</div>

                    <div class="presskit-title2 pt">Price</div>
                    <div class="presskit-text">???</div>-->
                    <div class="presskit-title2 pt">Website</div>
                    <div class="presskit-text">lok-digital.com</div>
                    <div class="presskit-title2 pt">Contact</div>
                    <div class="presskit-text">hello@lok-digital.com</div>


                </div>
                <div class="column3">
                    <div class="presskit-title1 pt pb">Pitch</div>
                    <div class="presskit-text">A whimsical adventure of magical words and their mind-bending mechanics
                    </div>
                    <div class="presskit-title1 pt pb">Description</div>
                    <div class="presskit-text">Embark on a whimsical puzzle solving journey of discovering unrecognizable words,
                        each with their own special powers.<br>
                        Find and spell these never-before-seen words, each with their own mind-bending ability to help change the world around you.
                        <br><br>
                        Learn the rules as you go and uncover how each magical word can be utilized to your advantage. <br>Uncover deep and thoughtful mechanics that will challenge and delight you as you uncover LOK’s unexpected twists and surprises.
                    </div>
                    <div class="presskit-title1 pt pb">Features</div>
                    <div class="presskit-text">Embark on a whimsical puzzle solving journey of discovering unrecognizable words,
                        each with their own special powers.<br>
                        Find and spell these never-before-seen words, each with their own mind-bending ability to help change the world around you.
                        <br><br>
                        Learn the rules as you go and uncover how each magical word can be utilized to your advantage. <br>Uncover deep and thoughtful mechanics that will challenge and delight you as you uncover LOK’s unexpected twists and surprises.
                    </div>
                </div>
            </div>
            <div class="presskit2">
                <div class="presskit-title1 pt pb">About the developers</div>
                <div class="presskit-text">
                    LOK Digital is a project born of an online collaboration between two artist/developers who will grab a drink together irl someday.
                    <br><br>
                    Blaž Urban Gracar (Letibus Design) is a Slovenian artist.
                    As a game designer, he created the critically acclaimed puzzle book LOK, as well as the award-winning games Abdec and All Is Bomb.
                    He is also a musician (composing award-winning music for the theatre, producing left-field electronica, playing keyboards),
                    a writer (publishing poetry, prose and comic books) and a filmmaker (editing and animating short films).
                    <br><br>
                    Ferran Ruiz Sala 'Raindrinker' (Icedrop Games) is a game developer from Barcelona who has a streak for pixelart, art in general and design.
                    Learnt game dev through game jams, both local and online, and after working for a couple of indie companies started developing his own projects and joined the Astra Fellowship.
                    He's now juggling way too many projects while teaching some classes on game development and pixel art.
                </div>
                <div class="presskit-title1 pt2 pb">About the publisher</div>
                <div class="presskit-text">
                    Draknek & Friends is ...
                </div>
                <div class="presskit-title1 pt2 pb">Videos</div>

                <div class="videos">

                <div class="div-video">
                    <div class="video">
                        <iframe class="video-iframe"
                                src="https://www.youtube.com/embed/v=U8p_XC-xY2w">
                        </iframe>
                    </div>
                </div>

                <div class="div-video">
                    <div class="video">
                        <iframe class="video-iframe"
                                src="https://www.youtube.com/embed/dyzWGS8ZT5Q">
                        </iframe>
                    </div>
                </div>

                <div class="div-video">
                    <div class="video">
                        <iframe class="video-iframe"
                                src="https://www.youtube.com/embed/cmSZ4RD3o6c">
                        </iframe>
                    </div>
                </div>
                </div>

                <div class="presskit-title1 pt2 pb">Screenshots</div>

                <div class="presskit-title1 pt2 pb">Gifs</div>

                <div class="images">
                    <div class="image-box">
                        <div class="image-box-pad">
                            <img src={gif1} class="screenshot-img"/>
                        </div>
                    </div>
                    <div class="image-box">
                        <div class="image-box-pad">
                            <img src={gif2} class="screenshot-img"/>
                        </div>
                    </div>
                    <div class="image-box">
                        <div class="image-box-pad">
                            <img src={gif3} class="screenshot-img"/>
                        </div>
                    </div>
                    <div class="image-box">
                        <div class="image-box-pad">
                            <img src={gif4} class="screenshot-img"/>
                        </div>
                    </div>
                </div>

                <div class="presskit-title1 pt2 pb">Key Art</div>

                <div class="presskit-title1 pt2 pb">Logos</div>
            </div>

            <div class="footer">
                <div class="footer-img letibus-icedrop">
                    <img src={credits} class="credits-img"/>
                </div>
                <div class="empty"></div>
                <div class="footer-img draknek">
                    <img src={credits2} class="credits-img"/>
                </div>
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
    import { onMount } from 'svelte';

    import logo from '$lib/images/lok-digital/logo.png';
    import lok_steam from '$lib/images/lok-digital/library_600x900_new.jpg';
    import credits from '$lib/images/lok-digital/credits.png';
    import credits2 from '$lib/images/lok-digital/DraknekFriendsLogo.png';

    import gif1 from "$lib/images/lok-digital/gif1.gif";
    import gif2 from "$lib/images/lok-digital/gif2.gif";
    import gif3 from "$lib/images/lok-digital/gif3.gif";
    import gif4 from "$lib/images/lok-digital/gif4.gif";

    let element;

    onMount(() => {
        element.scrollIntoView();
    });
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

        .presskit {
            flex-direction: column;
        }

        .column1 {
            padding: 0px !important;
            padding-bottom: 32px !important;
        }

        .column3 {
            padding: 0px !important;
        }

        .column2 {
            padding: 0px !important;
            padding-bottom: 32px !important;
        }

        .videos {
            flex-direction: column;
        }
    }

    .presskit {
        display: flex;
        font-family: CenturyLocal;
        text-align: left;
    }

    .presskit2 {
        display: flex;
        font-family: CenturyLocal;
        text-align: left;
        flex-direction: column;
    }

    .column1 {
        padding: 16px;
    }
    .column2 {
        padding: 16px;
        min-width: 200px;
    }
    .column3 {
        padding: 16px;
    }

    .presskit-title1 {
        font-size: 1.5em;
        font-weight: bold;
    }

    .presskit-title2 {
        font-size: 1.3em;
        font-weight: bold;
    }

    .pt {
        padding-top: 16px;
    }
    .pt2 {
        padding-top: 32px;
    }

    .pb {
        padding-bottom: 16px;
    }

    .presskit-text {
        font-size: 1.3em;
        padding-top: 4px;
        padding-bottom: 4px;
    }


    .videos {
        display: flex;
    }

    .div-video {
        padding-bottom: 16px;
        position: relative;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 8px;
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

</style>