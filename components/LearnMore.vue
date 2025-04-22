<template>
    <div class="button">
        <ul class="shadow-button-set">
        <li><button>Learn More</button></li>
        </ul>
    </div>
</template>

<script setup>

</script>

<style lang="postcss" scoped>


.shadow-button-set {
margin: 0;
display: flex;
flex-direction: column;
align-items: flex-start;
gap: 20px;

& > li {
display: inline-flex;
background: var(--accent);

&:is(:hover, :focus-within) > button:not(:active) {
  --distance: -5px;
}
}

& button {

font-family: 'NEXON Lv1 Gothic OTF';
appearance: none;
outline: none;
font-size: 16px;
color: var(--accent);
border: 1px solid var(--accent);
background: white;

--distance: 0;
transform: translateX(var(--distance)) translateY(var(--distance));

@media (prefers-reduced-motion: no-preference) {
  will-change: transform;
  transition: transform .2s ease ;
}
}
}


.button {
    min-block-size: 100%;
    place-content: center;
}
</style>