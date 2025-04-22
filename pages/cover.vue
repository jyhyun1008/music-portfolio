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
                <h2>Cover</h2>
                <div class="content">
                    <h3>25.04.12.</h3>
                    <ul>
                        <li>고민중독 (Origin: QWER) <code>K-Pop</code>
                            <iframe width="100%" style="aspect-ratio: 16 / 9" src="https://www.youtube.com/embed/5gtRxFOqF2U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        </li>
                    </ul>
                </div>
                <div class="content">
                    <h3>25.04.06.</h3>
                    <ul>
                        <li>だから僕は音楽を辞めた (Origin: ヨルシカ) <code>J-Pop</code>
                            <iframe width="100%" style="aspect-ratio: 16 / 9" src="https://www.youtube.com/embed/OGkMVfxaHfU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        </li>
                    </ul>
                </div>

                <div class="content">
                    <h3>25.03.30.</h3>
                    <ul>
                        <li>Imprisoned XII (Origin: Ave Musica) <code>Anime</code>
                            <iframe width="100%" style="aspect-ratio: 16 / 9" src="https://www.youtube.com/embed/4lKxDmSfBxA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        </li>
                    </ul>
                </div>
                <div class="content">
                    <h3>25.03.23.</h3>
                    <ul>
                        <li>私、アイドル宣言 (Origin: HoneyWorks) <code>J-pop</code>
                            <iframe width="100%" style="aspect-ratio: 16 / 9" src="https://www.youtube.com/embed/ua-LTgzpf_c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        </li>
                    </ul>
                </div>
                <div class="content">
                    <h3>25.03.11.</h3>
                    <ul>
                        <li>キズナミュージック♪  (Origin: Poppin' Party) <code>Anime</code>
                            <iframe width="100%" style="aspect-ratio: 16 / 9" src="https://www.youtube.com/embed/NLZa9x9VWYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        </li>
                    </ul>
                </div>

                <div class="content">
                    <h3>25.03.04.</h3>
                    <ul>
                        <li>太陽は何度でも (Origin: NGT48) <code>J-Pop</code>
                            <iframe width="100%" style="aspect-ratio: 16 / 9" src="https://www.youtube.com/embed/Tl9XYm8Q2yE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        </li>
                    </ul>
                </div>

                <div class="content">
                    <h3>25.03.02.</h3>
                    <ul>
                        <li>ガーネット (Origin: 奥華子) <code>J-Pop</code>
                            <iframe width="100%" style="aspect-ratio: 16 / 9" src="https://www.youtube.com/embed/zqh2mru8Oy8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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