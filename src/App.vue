<template>
  <div class="app">
    <header>
      <h1>The<strong>Anime</strong>App</h1>
      <form class="search_box">
      <input
        type="search"
        class="Search-field"
        placeholder="Search for an anime..."
      />
    </form>
    </header>

    <main>
      <div class="cards">
<Card />
      </div>
    </main>
  </div>
</template>

<script>
import Card from "./components/Card"
export default {
  components: {
    Card
  }
  // setup() {
  //   return {
  //     Card
  //     }
  // }
};
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
  .search_box{
  text-align: center;
  input{
    width: 100%;
    max-width: 600px;
    margin: 30px auto;
    border: none;
    height: 50px;
    padding: 5px 10px;
    outline: none;
    background: none;
    appearance: none;
    background-color: #f3f3f3;
    box-shadow: 0px 4px 8px rgba($color: #000000, $alpha: 0.15);
    border-radius: 10px;
    color: #313131;
    font-size: 20px;
    transition: 0.4s;

    &::placeholder{
      color: #aaa;
    }
  }
}
}
main{
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 30px;

  .cards{
    display: flex;
    flex-wrap: wrap;
    margin: 0 -8px;
  }
}
</style>
