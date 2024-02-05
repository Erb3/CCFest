<template>
  <nav>
    <h2><NuxtLink to="/home">🎉 CCFest</NuxtLink></h2>
    <div class="spacer"></div>
    <NuxtLink to="/about">About</NuxtLink>
  </nav>
</template>

<style scoped>
nav {
  width: 100%;
  background-color: var(--lifted);
  margin-top: 1rem;
  display: flex;
  align-items: center;
  gap: 0.7rem;
  box-shadow: 0 0 10px 2px #0000001a;
  border-radius: 1rem;
  padding: 1.25rem;
}

.spacer {
  margin: auto;
}

img {
  aspect-ratio: 1;
  width: 3vw;
}

h2,
h2 > a {
  font-family: 'Protest Riot', sans-serif;
  font-size: 2.5rem;
  margin: 0;
  color: var(--text);
  text-decoration: none;
}
</style>
