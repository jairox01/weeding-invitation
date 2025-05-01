<template>
  <div class="container">
    <div class="masonry">
      <div class="column left">
        <div class="item">
          <img src="../assets/img/masonry-1.jpg" alt="">
        </div>
        <div class="row">
          <div class="item small">
            <img src="../assets/img/masonry-2.jpg" alt="">
          </div>
          <div class="item small">
            <img src="../assets/img/masonry-3.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="column right">
        <div class="item">
          <img src="../assets/img/masonry-4.jpg" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'MasonryComponent'
};
</script>