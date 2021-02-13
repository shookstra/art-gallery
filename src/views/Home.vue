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
        <div class="post-paragraphs">
          <p>A commision portrait piece.</p>
          <p class="post-medium">Acrylic on canvas</p>
          <p class="post-date">February 2021.</p>
        </div>
      </div>
      <div class="post">
        <h2 class="post-title">Snowy Building</h2>
        <img
          src="../images/snowy-buildings.jpg"
          height="310"
          class="post-main-image"
        />
        <div class="post-paragraphs">
          <p>
            Inspired by a reddit post. Link posted soon. Created entirely using
            a palette knife.
          </p>
          <p class="post-medium">Acrylic on canvas</p>
          <p class="post-date">February 2021.</p>
        </div>
      </div>
      <div class="post">
        <h2 class="post-title">Flowers</h2>
        <img
          src="../images/flowers.jpg"
          height="1350"
          class="post-main-image"
        />
        <div class="post-paragraphs">
          <p>A field of flowers.</p>
          <p class="post-medium">Acrylic on canvas</p>
          <p class="post-date">Febrary 2021.</p>
        </div>
      </div>
      <div class="post">
        <h2 class="post-title">Lemon</h2>
        <img src="../images/lemon.jpg" height="1350" class="post-main-image" />
        <img src="../images/real-lemon.jpg" height="250" class="" />
        <div class="post-paragraphs">
          <p>
            Still life painting of a lemon. Plate and lemon done completely with
            a palette knife.
          </p>
          <p class="post-medium">Acrylic on canvas</p>
          <p class="post-date">January 2021.</p>
        </div>
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
        <div class="post-paragraphs">
          <p>Series of three works. Clouds. More pictures to come.</p>
          <p class="post-medium">Acrylic on canvas</p>
          <p class="post-date">December 2020.</p>
        </div>
      </div>
      <div class="post">
        <h2 class="post-title">Treeline</h2>
        <img
          src="../images/treeline.jpg"
          height="1350"
          class="post-main-image"
        />
        <div class="post-paragraphs">
          <p>Night sky and treeline. First painting since 2017.</p>
          <p class="post-medium">Acrylic on canvas</p>
          <p class="post-date">December 2020.</p>
        </div>
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
  /* background-color: rgba(240, 240, 255); */
}

.home-title {
  font-size: 2.5rem;
  margin: 0 auto;
  width: 700px;
  padding: 0px 0px 5px 0px;
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
  /* color: rgb(30, 30, 70); */
}

.post {
  padding: 25px 10px 10px 10px;
  background-color: rgba(240, 240, 255);
  margin: 5px 0px;
  border-radius: 5px;
  color: rgb(60, 60, 120);
  /* border: 2px solid rgb(60, 60, 120); */
  box-shadow: 0px 0px 5px 0px rgba(0, 0, 0, 0.15);
}

.post-title {
  padding-bottom: 15px;
  color: rgb(50, 50, 100);
  font-size: 2rem;
}

.post-main-image {
  margin: 0 auto;
  text-align: center;
  border-radius: 5px;
}

.post-paragraphs {
  background-color: #ffcad4;
  padding: 10px 15px;
  border-radius: 5px;
}

.post-medium {
  font-weight: bold;
  /* color: rgb(80, 80, 140); */
}

.post-date {
  font-style: italic;
  /* color: rgb(80, 80, 140); */
}
</style>
