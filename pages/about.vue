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
                <h2>About</h2>
                <div>Blending J-POP-inspired band sounds and anime aesthetics with the percussive edge of traditional Korean instruments, she creates a distinctive style that bridges modern emotion with cultural heritage. </div>
                <div>Through the integration of instruments such as <i>geomungo</i>, <i>haegeum</i>, and <i>pipa</i> into a core ensemble of drums, bass, and piano, each arrangement brings a contemporary narrative to life, colored with the textures of Korean tradition.</div>
                <div>To showcase this unique arrangement style, widely recognized songs are reinterpreted with traditional Korean instrumentation. Original compositions are also occasionally produced to further explore and express this musical direction.</div>
                <div>Currently pursuing studies in both mixing and traditional Korean music theory, she continues to refine her craft.</div>
                <h2>As a Virtual Singer-Songwriter</h2>
                <div>Under the name <b><i>However Ina</i></b>, she uploads weekly cover songs and release original singles every two to three months.</div>
                <div>From arrangement and vocals to mixing, mastering, video editing, and illustration, all aspects of content creation are handled independently. This comprehensive skill set enables the production of high-quality content as a solo creator.</div>
                <h2>Skills</h2>
<b>Music</b>
<ul>
    <li><b>Music Arrangement</b> – <code>Intermediate</code>
    <ul><li>Specialized in J-POP style arrangements with integrated Korean traditional instruments (e.g., <i>geomungo, haegeum, pipa</i>).</li></ul>
    </li>
    <li><b>Logic Pro X</b> – <code>Intermediate</code>
    <ul><li>Proficient in music production, MIDI programming, and audio editing.</li></ul>
    </li>
    <li><b>Bass Guitar</b> – <code>Beginner</code>
        <ul><li>Over 2 years of experience performing in live worship band settings at <i>Suwon Jeil</i> Church.</li></ul>
    </li>
    <li><b>Korean Traditional Music (Gugak) Theory</b> – <code>Beginner</code>
    <ul><li>Studying the fundamentals of traditional Korean scales, rhythms, and instrumentation.</li></ul>
</li></ul>

<b>Others</b>
<ul>
<li><b>Final Cut Pro / Blender</b> – <code>Basic to Intermediate</code>
    <ul><li>Capable of video editing and basic 3D visualization.</li></ul>
</li>
    <li><b>Web Programming</b> – <code>Intermediate</code>
    <ul><li>Familiar with HTML, CSS, JavaScript, and frameworks such as React and Vue.</li></ul>
</li>
    <li><b>Digital Illustration</b> – <code>Intermediate</code>
    <ul><li>Skilled in character and concept art using Clip Studio Paint.</li></ul>
    </li></ul>
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