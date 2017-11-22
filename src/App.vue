<template>
  <div id="app">
    <carousel 
      :perPage="1"
      :autoplay="true"
      :autoplayTimeout="3000"
      :loop="true"
      :paginationEnabled="false">
      <slide>
        <div class="header">Content ONE</div>
        <div class="container">
          <div class="col one">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
          <div class="col two">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
        </div>
      </slide>
      <slide>
        <div class="header">Content Two</div>
        <div class="container">
          <div class="col one">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
          <div class="col two">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
        </div>
      </slide>
      <slide>
        <div class="header">Content Tree</div>
        <div class="container">
          <div class="col one">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
          <div class="col two">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
        </div>
      </slide>
      <slide>
        <div class="header">Content Four</div>
        <div class="container">
          <div class="col one">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
          <div class="col two">
            <h3>Col One</h3>
            <span>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum fugit nulla veniam! Voluptates magni optio assumenda ipsam tempore et fuga cumque. Eum numquam magni earum officia modi soluta vero. Officiis.</span>
          </div>
        </div>
      </slide>
    </carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel'
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    Carousel,
    Slide
  }
}
</script>

<style lang="scss">
.container{
  width: 100%;
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
}
.col{
  // width: 50%;
  width: 30rem;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

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
</style>
