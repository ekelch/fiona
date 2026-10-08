<script>
    import plasma from "/src/lib/assets/plasma.mp4"
</script>

<div class="main-outer">
    <video autoplay loop muted class="video-container">
        <source src={plasma}>
    </video>
</div>

<style>
    :global(body) {
        margin: 0;
    }

    .main-outer {
        width: 100vw;
        height: 100vh;
        background-color: hsl(0 0 2.5%);
        display: flex;
    }

    .video-container {
        height: 100%;
        margin: auto;
    }
</style>