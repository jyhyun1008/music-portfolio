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
                <h2>New Release</h2>
                <div class="content">
                    <h3>APR 18, 2025</h3>
                    <ul>
                        <li>제망매가(Jemangmaega) - 연이나(However Ina) <code>Original</code></li>
                    </ul>
                </div>
                <div class="content">
                    <h3>APR 12, 2025</h3>
                    <ul>
                        <li>고민중독 (Origin: QWER) <code>Cover</code></li>
                    </ul>
                </div>
            </div>
            <div id="about">
                <h2>About</h2>
                <div>Blending J-POP-inspired band sounds and anime aesthetics with the percussive edge of traditional Korean instruments, she creates a distinctive style that bridges modern emotion with cultural heritage. </div>
                <a href="/about"><LearnMore /></a>
            </div>

            <div id="contact">
                <h2>Contact</h2>
                <a href="/contact"><LearnMore /></a>
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

#news, #about, #contact {
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