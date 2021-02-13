<template>
  <div class="home">
    <h1 class="home-title">Posts</h1>
    <div class="posts">
      <div class="post">
        <h2 class="post-title">Momtez (working title)</h2>
        <img
          src="../images/momtez-finished.jpg"
          height="1350"
          class="post-main-image"
        />
        <p>A commision portrait piece.</p>
        <p>Acrylic on canvas</p>
        <p class="post-date">February 2021.</p>
      </div>
      <div class="post">
        <h2 class="post-title">Snowy Building</h2>
        <img
          src="../images/snowy-buildings.jpg"
          height="310"
          class="post-main-image"
        />
        <p>
          Inspired by a reddit post. Created entirely using a palette knife.
        </p>
        <p>Acrylic on canvas</p>
        <p class="post-date">February 2021.</p>
      </div>
      <div class="post">
        <h2 class="post-title">Flowers</h2>
        <img
          src="../images/flowers.jpg"
          height="1350"
          class="post-main-image"
        />
        <p>A field of flowers.</p>
        <p>Acrylic on canvas</p>
        <p class="post-date">Febrary 2021.</p>
      </div>
      <div class="post">
        <h2 class="post-title">Lemon</h2>
        <img src="../images/lemon.jpg" height="1350" class="post-main-image" />
        <img src="../images/real-lemon.jpg" height="250" class="" />
        <p>
          Still life painting of a lemon. Plate and lemon done completely with a
          palette knife.
        </p>
        <p>Acrylic on canvas</p>
        <p class="post-date">January 2021.</p>
      </div>
      <div class="post">
        <h2 class="post-title">Cloud Series</h2>
        <img
          src="../images/pink-cloud.jpg"
          height="1350"
          class="post-main-image"
        />
        <img
          src="../images/orange-cloud-1.jpg"
          height="1350"
          class="post-main-image"
        />
        <p>Series of three works. Clouds</p>
        <p>Acrylic on canvas</p>
        <p class="post-date">December 2020.</p>
      </div>
      <div class="post">
        <h2 class="post-title">Treeline</h2>
        <img
          src="../images/treeline.jpg"
          height="1350"
          class="post-main-image"
        />
        <p>Night sky and treeline. First painting since 2017.</p>
        <p>Acrylic on canvas</p>
        <p class="post-date">December 2020.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>

<style scoped>
.home {
  /* padding: 30px 5px; */
  /* border: 1px solid red; */
}

.home-title {
  margin: 0 auto;
  width: 700px;
}

.posts {
  padding-right: 10px;
  display: flex;
  flex-direction: column;
  height: 100%;
  overflow-x: scroll;
  width: 700px;
  /* border: 1px solid red; */
  margin: 0 auto;
  color: rgb(50, 50, 100);
}

.post {
  padding: 20px 10px;
  background-color: rgba(230, 230, 250);
  margin: 10px 0px;
  border-radius: 5px;
  /* border: 1px solid blue; */
}

.post-title {
  padding-bottom: 15px;
}

.post-main-image {
  margin: 0 auto;
  text-align: center;
  border-radius: 5px;
}

.post-date {
  font-style: italic;
  color: rgb(120, 120, 180);
}
</style>
