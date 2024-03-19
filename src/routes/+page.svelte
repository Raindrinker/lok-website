<div class="about">
    <div class="content">
        <img src={logo} class="logo"/>
        UNDER CONSTRUCTION
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
    import credits2 from '$lib/images/lok-digital/DraknekFriendsLogo.png';
    import steam_logo from '$lib/images/steam.png';
    import decoration1 from '$lib/images/lok-digital/decoration1.png';
    import decoration2 from '$lib/images/lok-digital/decoration2.png';

    import lokites1 from '$lib/images/Figures1.jpg';
    import lokites2 from '$lib/images/Figures2.jpg';

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
        height: 100vh;

        font-weight: bold;
        font-size: 1.5em;
    }

    .logo {
        padding-bottom: 32px;
        max-width: 300px;
    }


</style>