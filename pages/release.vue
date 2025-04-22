import { LearnMore } from '../.nuxt/components';
<template>
    <div id="app">
        <Navbar />
        <div id="container">
            <div id="header">
                <h1>Hyun Jaeyeon</h1>
                <div>Music Composer, Arranger, Producer, Engineer</div>
            </div>
            <div id="news">
                <h2>Release</h2>
                <div class="content">
                    <h3>APR 18, 2025</h3>
                    <ul>
                        <li>제망매가(Jemangmaega)
                            <iframe width="100%" style="aspect-ratio: 1" src="https://www.youtube.com/embed/kpiNzO5pnqA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="postcss">

#app {
    display: flex;
    height: 100dvh;
    justify-content: center;
    align-items: center;
}

#container {
    height: calc(100dvh - 20px);
    width: calc(100% - 200px);
    max-height: 700px;
    max-width: 560px;
    margin: 10px;
    border: 1px solid var(--accent);
    background-color: white;
    overflow: auto;
}

#header {
    background-image: url('https://images.pexels.com/photos/2102907/pexels-photo-2102907.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2');
    background-position: center;
    background-size: cover;
    height: 200px;
    display: flex;
    flex-direction: column;
    justify-content: end;
    align-items: end;
    padding: 10px;
    border-bottom: 1px solid var(--accent);
    color: white;
}

#news {
    padding: 10px;
    display: flex;
    flex-direction: column;
    gap: 10px;

  line-height: 1.8;
}

.content {
    padding: 10px;
    border: 1px solid var(--accent);
}
</style>