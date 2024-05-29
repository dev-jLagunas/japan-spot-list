<script setup>
import "fullpage.js/dist/fullpage.css";
import fullpage from "fullpage.js";

new fullpage("#fullpage", {
  // options here
  licenseKey: "OPEN-SOURCE-GPLV3-LICENSE",
  autoScrolling: true,
  scrollHorizontally: true,
});
</script>

<template>
  <div id="fullpage">
    <div class="section">
      <div class="slide">
        <h1>Slide 1.1</h1>
        <p>This is some content for slide 1.1.</p>
      </div>
      <div class="slide">
        <h1>Slide 1.2</h1>
        <p>This is some content for slide 1.2.</p>
      </div>
      <div class="slide">
        <h1>Slide 1.3</h1>
        <p>This is some content for slide 1.3.</p>
      </div>
    </div>
    <div class="section">
      <div class="slide">
        <h1>Slide 2.1</h1>
        <p>This is some content for slide 2.1.</p>
      </div>
      <div class="slide">
        <h1>Slide 2.2</h1>
        <p>This is some content for slide 2.2.</p>
      </div>
      <div class="slide">
        <h1>Slide 2.3</h1>
        <p>This is some content for slide 2.3.</p>
      </div>
    </div>
    <!-- Add more sections and slides as needed -->
  </div>
</template>
<style lang="scss" scoped>
.section {
  text-align: center;
  color: white;
}

.section .slide {
  background: #3f51b5;
  padding: 20px;
}
</style>
