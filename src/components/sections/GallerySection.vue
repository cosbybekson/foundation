<template>
  <div class="container-fluid ">
    <h1 class="gallery-title mt-5 mb-5">The Gallery</h1>
    <div class="row">
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan.jpg" alt="" />
      </div>
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan1.jpg" alt="" />
      </div>
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan8.jpg" alt="" />
      </div>
    </div>
    <div class="row">
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan3.jpg" alt="" />
      </div>
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan4.jpg" alt="" />
      </div>
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan5.jpg" alt="" />
      </div>
    </div>
    <div class="row">
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan6.jpg" alt="" />
      </div>
      <div class="col">
        <img class="img-fluid" src="@/assets/oephan7.jpg" alt="" />
      </div>
      <div class="col">
        <img class="img-fluid" src="@/assets/orphan2.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "GallerySection",
};
</script>

<style scoped>
.gallery-title {
  color: #090909;
  text-align: center;
  font-family: Bebas Neue;
  font-size: 60px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px;
}
</style>
