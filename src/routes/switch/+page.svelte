<div class="about">
    <div class="content">
        <div class="decor1">
            <img src={decoration1}/>
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
    import {onMount} from "svelte";

    onMount(() => {
        window.location.href = 'https://www.draknek.org/nintendo/lok-digital';
    });
</script>

<style>
    .content {
        height: 100vh;
    }
</style>