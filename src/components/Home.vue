<template>
  <div class="home">
    <div>
      <Slider/>
      <TopProducts />
    </div>
  </div>
</template>

<script>
import TopProducts from './TopProducts'
import Slider from './HomeSlider'
export default {
  name: 'home',
  components: { TopProducts, Slider },
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
button {
  border: hidden;
  border-radius: 15;
  padding:10px;
  background: inherit;
}
button:hover {
  border: groove;
  background: inherit;
  width: 300px;
  height: 350px;
}
</style>
