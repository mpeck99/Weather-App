<template>
  <footer>
    <p>Morgan Peck - Weather App @{{ new Date().getFullYear() }}</p>
    <p>Built with <a href="https://v3.vuejs.org/">Vue 3</a></p>
    <p>
      Icons made by
      <a href="https://www.flaticon.com/authors/fjstudio" title="fjstudio"
        >fjstudio</a
      >
      and <a href="https://www.freepik.com" title="Freepik">Freepik</a>
      from
      <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
    </p>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import '../assets/styles/styles.scss';

footer {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  padding: 0.75rem 1rem;

  color: $white;
  text-align: center;

  background: $black;

  border-image-source: linear-gradient(to left, $pink, $teal, $purple);
  border-top: 10px solid;
  border-bottom: none;
  border-right: none;
  border-left: none;
  border-image-slice: 1;
  border-width: 0.5rem;

  a,
  a:visited {
    color: $white;
  }

  @media (min-width: 840px) {
    flex-direction: row;
    justify-content: space-between;
  }
}
</style>
