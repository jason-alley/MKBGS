<script lang="ts">
    import logo from '$lib/assets/Logos/TBK_Icon_01b.png';
    import steamLogo from '$lib/assets/Logos/steam-logo.png';
</script>

<header class="header">
    <hgroup class="header-content">
        <div>
            <img class="logo" src={logo} alt="Team Broke Kids Logo">
            <span>Team Broke Kids</span>
        </div>
        <div>
            <span>Download Now</span>
            <img src={steamLogo} alt="Steam logo download button.">
        </div>
    </hgroup>
</header>

<style>
    :root {
        --main-bg-color: #2C2C2C;
        --header-font-color: #FFFFFF;
        --header-font-size: 1.2rem;
        --main-font-family: 'Open Sans', sans-serif;
    }

    .header {
    min-width: 60vw;
    border: 1px solid black;
    background-color: var(--main-bg-color);
    color: var(--header-font-color);

    .header-content,
    .header-content div {
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: var(--header-font-size);
        font-family: var(--main-font-family);
    }

}

.logo {
    width: 60px;
    height: 60px;
}
</style>
