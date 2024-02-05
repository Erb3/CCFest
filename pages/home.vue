<template>
  <section>
    <NuxtLink to="/event/jam2024">
      <article>
        <h3>CCFest Jam 2024</h3>
        <p>4. mar 12:00 --> 24. mar 12:00</p>
      </article>
    </NuxtLink>
  </section>
</template>

<style scoped>
section {
  margin: 2vh 0;
}

article {
  background-color: var(--lifted);
  width: 100%;
  padding: 1.25rem;
  border-radius: 0.5rem;
  text-align: center;
  transition: background-color 0.15s;
}

article:hover {
  background-color: var(--lifted-hover);
}

a {
  text-decoration: none;
  color: var(--main-text);
}

h3 {
  font-size: 2rem;
  margin: 2vh 2vw;
}
</style>
