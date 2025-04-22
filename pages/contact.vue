import { LearnMore } from '../.nuxt/components';
<template>
    <div id="app">
        <Navbar />
        <div id="container">
            <div id="header">
                <h1>Hyun Jaeyeon</h1>
                <div>Music Composer, Arranger, Producer, Engineer</div>
            </div>
            <div id="about">
                <h2>Contact</h2>
                <ul>
                    <li>E-Mail: jayhyun1008@gmail.com</li>
                    <li>YouTube: @however_ina_main</li>
                </ul>
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

#about {
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