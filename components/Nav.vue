<template>
  <section class="container">
    <div class = "Header_Links">
      <nuxt-link
        to="/"
        class="Header__Link">
        <p class="Header_Link"> Keyboard Chart</p>
      </nuxt-link>

      <nuxt-link
        to="/line"
        class="Header__Link">
        <p class="Header_Link2"> Line Chart</p>
      </nuxt-link>

      <nuxt-link
        to="/mix"
        class="Header__Link">
        <p class="Header_Link3"> Mix Chart</p>
      </nuxt-link>

      <nuxt-link
        to="/guide"
        class="Header__Link">
        <p class="Header_Link4"> Guide Page</p>
      </nuxt-link>
    </div>
  </section>
</template>

<style>
.Header_Links{
  box-sizing: border-box;
  display: flex;
  justify-content:center;
  margin: 0;
  margin-right:10px;
}
.Header_Link{
  display: flex;
  justify-content:center;
  margin: 0;
  margin-right:10px;
}
.Header_Link2{
  display: flex;
  justify-content:center;
  margin: 0;
  margin-right:10px;
}
.Header_Link3{
  display: flex;
  justify-content:center;
  margin: 0;
  margin-right:10px;
}
.Header_Link4{
  display: flex;
  justify-content:center;
  margin: 0;
  margin-right:10px;
}



</style>
