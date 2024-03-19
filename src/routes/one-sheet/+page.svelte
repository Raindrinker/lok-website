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
                <b>A charmingly playful adventure of word and rule discovery.</b> <br><br>

                Embark on a whimsical puzzle solving journey as you discover magical and unrecognizable words, each with their own special powers. Enter into the enchanting LOK universe filled with delight and oozing with charm. Find and spell magical words to summon adorable creatures, each with their own special ability to help change the world around you.

                <br><br>

                Discover the rules as you go, learning how each special word can be used to your advantage, helping you piece together the secrets of this strange world. With simple, cozy mechanics and deep mind-bending gameplay full of unexpected twists, LOK Digital invites you to tap into your logic side while curling up to enjoy the enchanting gameplay.

            </div>

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

            <div class="list text">
                <ul>
                    <li>Approachable and intuitive gameplay suitable for players of all skill levels and ages</li>
                    <li>Daily puzzles with player leaderboards to keep players coming back for more and keep retention high</li>
                    <li>Perfect for pick up and play sessions with intuitive mechanics, high replayability, and high skill ceiling</li>
                    <li>Meditative, entrancing soundtrack and elegant, hand-drawn art style</li>
                    <li>Learn deep and surprising mechanics that simultaneously challenge and delight as the game thoughtfully teaches the rules in an engaging and intuitive manner</li>
                    <li>Published by the award-winning puzzle experts, Draknek & Friends, the team behind A Monster’s Expedition, Cosmic Express, Bonfire Peaks, and more</li>
                </ul>
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

    .about {
        display: flex;
        flex-direction: column;
        align-items: center;

        width: 100%;

        font-family: CenturyLocal;

        background: #EEEEEE url("../images/lok-digital/lok-bg.jpeg");
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