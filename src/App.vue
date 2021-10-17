<template>
  <div class="app">
    <header>
      <h1>The<strong>Anime</strong>App</h1>
    </header>

    <form class="search_box">
      <input
        type="search"
        class="Search-field"
        placeholder="Search for an anime..."
      />
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Fira Sans", sans-serif;
}
a {
  text-decoration: none;
}
header {
  padding: 50px 0;
  h1 {
    color: #888;
    font-size: 42px;
    font-weight: 400;
    text-align: center;
    text-transform: uppercase;
  }
  strong {
    color: #313131;
  }
}
</style>
