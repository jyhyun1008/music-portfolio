<template>
  <div>
    <NuxtPage />
  </div>
</template>

<style>
@font-face {
	font-family: 'NEXON Lv1 Gothic OTF';
	src: url('https://fastly.jsdelivr.net/gh/projectnoonnu/noonfonts_20-04@2.1/NEXON Lv1 Gothic OTF.woff') format('woff');
	font-weight: normal;
	font-style: normal;
}

@font-face {
	font-family: 'NEXON Lv1 Gothic OTF';
	src: url('https://fastly.jsdelivr.net/gh/projectnoonnu/noonfonts_20-04@2.1/NEXON Lv1 Gothic OTF Bold.woff') format('woff');
	font-weight: 700;
	font-style: normal;
}

:root {
  --accent: #ff4768;
  --bg: #f7f7f9;
}

body {
  font-family: 'NEXON Lv1 Gothic OTF';
  color: var(--accent);
  background-color: var(--bg);
}

* {
  box-sizing: border-box;
  margin: 0;
}

html {
  block-size: 100%;
}

a {
    color: inherit;
    text-decoration: none;
}


code {
  padding: 3px;
  background-color: var(--bg);
  border: 1px solid var(--accent);
}
</style>