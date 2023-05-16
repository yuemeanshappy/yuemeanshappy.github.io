---
layout: single
author_profile: true
---

<div class="photos">
  <!-- First Row -->
  <div class="photo">
    <img src="/assets/images/peony.JPG" alt="Peony">
    <p class="caption" data-title="Peony" data-date="New York Botanic Garden, 04/2023"></p>
  </div>
  <div class="photo">
    <img src="/assets/images/peony2.JPG" alt="Peony">
    <p class="caption" data-title="Peony" data-date="New York Botanic Garden, 04/2023"></p>
  </div>

  <!-- Second Row -->
  <div class="photo">
    <img src="/assets/images/iris.JPG" alt="iris">
    <p class="caption" data-title="Iris" data-date="Hangzhou Botanic Garden, 03/2021"></p>
  </div>
  <div class="photo">
    <img src="/assets/images/tea-flower.JPG" alt="tea flower">
    <p class="caption" data-title="Tea Flower" data-date="Hangzhou Botanic Garden, 03/2021"></p>
  </div>

  <!-- Third Row -->
  <div class="photo">
    <img src="/assets/images/cherry-blossom.JPG" alt="cherry blossom">
    <p class="caption" data-title="Cherry Blossom" data-date="Riverside Park, 04/2023"></p>
  </div>
  <div class="photo">
    <img src="/assets/images/lilac.JPG" alt="lilac">
    <p class="caption" data-title="Lilac" data-date="New York Botanic Garden, 04/2023"></p>
  </div>

  <!-- Fourth Row -->
  <div class="photo">
    <img src="/assets/images/american-robin.JPG" alt="american robin">
    <p class="caption" data-title="American Robin" data-date="Central Park, 05/2023"></p>
  </div>
  <div class="photo">
    <img src="/assets/images/canadian-goose.JPG" alt="canadian goose">
    <p class="caption" data-title="Canadian Goose" data-date="Central Park, 05/2023"></p>
  </div>

  <!-- 5th Row -->
  <div class="photo">
    <img src="/assets/images/squirrel.JPG" alt="squirrel">
    <p class="caption" data-title="Squirrel" data-date="Riverside Park, 04/2023"></p>
  </div>
  <div class="photo">
    <img src="/assets/images/chipmunk.JPG" alt="chipmunk">
    <p class="caption" data-title="Eastern Chipmunk" data-date="Central Park, 05/2023"></p>
  </div>

  <!-- 6th Row -->
  <div class="photo">
    <img src="/assets/images/nybg2.JPG" alt="nybg">
    <p class="caption" data-title="New York Botanic Garden" data-date="04/2023"></p>
  </div>
  <div class="photo">
    <img src="/assets/images/nybg.JPG" alt="nybh">
    <p class="caption" data-title="New York Botanic Garden" data-date="04/2023"></p>
  </div>

</div>

<style>
.photos {
  max-width: 100%; /* Change this value to adjust the width of the container */
  margin-left: auto;
  margin-right: auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.photo {
  width: calc(50% - 10px); /* Adjust this value to change the spacing between photos */
  margin-bottom: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.photo img {
  display: block;
  width: 100%;
  height: auto;
}

.photo .caption {
  text-align: center;
  font-size: 0.7em;
  line-height: 1.2;
}

.photo .caption:before {
  content: attr(data-title);
  font-weight: bold;
}

.photo .caption:after {
  content: attr(data-date);
  display: block;
}




