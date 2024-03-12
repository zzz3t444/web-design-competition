<template>
  <div
    class="gallery-grid rounded-2xl duration-100 hover:border-blue-400 hover:shadow-lg hover:shadow-blue-600/20 dark:hover:border-blue-300/30"
  >
    <img src="../assets/img/assetpeople/Keyza.jpg" alt="" />
    <img src="../assets/img/assetpeople/nanda.jpg" alt="" />
    <img src="../assets/img/assetpeople/celis.jpg" alt="" />
    <img src="../assets/img/assetpeople/fael.jpg" alt="" />
    <img src="../assets/img/assetpeople/acham.png" alt="" />
    <img src="../assets/img/assetpeople/denis.jpg" alt="" />
    <img src="../assets/img/assetpeople/zet.jpg" alt="" />
  </div>
</template>

<script>
import "../assets/css/responsive.css";
</script>

<style>
.gallery-grid {
  --size: min(95vmin, 500px);
  width: var(--size);
  height: var(--size);
  display: grid;
  grid-template-rows: 50% 50%;
  overflow: hidden;
  gap: 6px;
  margin-top: 13px;
}

.gallery-grid img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

@keyframes moveHorizontal {
  to {
    object-position: 100% 0;
  }
}

@keyframes moveVertical {
  to {
    object-position: 0 100%;
  }
}

@keyframes shrinkVertical {
  to {
    height: 0;
  }
}

@keyframes shrinkHorizontal {
  to {
    width: 0;
  }
}

@keyframes growHorizontal {
  to {
    width: 100%;
  }
}
@keyframes growHorizontal2 {
  to {
    width: 70%;
  }
}

@keyframes growVertical {
  to {
    height: 100%;
  }
}

@keyframes growAll {
  to {
    width: 100%;
    height: 100%;
  }
}

.gallery-grid img:nth-child(1) {
  grid-column: 1;
  grid-row: 1;
  justify-self: end;
  animation: moveHorizontal 8.5s 0.5s 1, shrinkHorizontal 2s 9s ease-in 1;
  animation-fill-mode: forwards;
}

.gallery-grid img:nth-child(2) {
  grid-column: 2;
  grid-row: 1;
  justify-self: end;
  animation: shrinkHorizontal 2s 11s 1;
  animation-fill-mode: forwards;
}

.gallery-grid img:nth-child(3) {
  grid-row: 2;
  grid-column: 1 / 3;
  align-self: end;
  object-position: 0 0;
  animation: moveVertical 5s 1s 1, shrinkVertical 3s 5s 1;
  animation-fill-mode: forwards;
}

.gallery-grid img:nth-child(4) {
  grid-column: 1 / 3;
  grid-row: 1;
  width: 0;
  justify-self: center;
  align-self: start;
  animation: growHorizontal 2.25s 11s 1, moveHorizontal 4s 14s 1, shrinkVertical 2s 18s 1;
  animation-fill-mode: forwards;
}

.gallery-grid img:nth-child(5) {
  grid-column: 1;
  grid-row: 2;
  width: 0;
  justify-self: start;
  align-self: end;
  animation: growHorizontal 2.5s 7.5s 1, moveVertical 4s 12.5s 1, shrinkHorizontal 2s 17s 1;
  animation-fill-mode: forwards;
}

.gallery-grid img:nth-child(6) {
  grid-column: 2;
  grid-row: 2;
  width: 0;
  justify-self: end;
  align-self: end;
  animation: growHorizontal 2s 8s 1, shrinkHorizontal 2s 17s 1;
  animation-fill-mode: forwards;
}

.gallery-grid img:nth-child(7) {
  grid-column: 1/3;
  grid-row: 1/3;
  width: 0;
  justify-self: end;
  align-self: end;
  object-position: 0 0;
  animation: growHorizontal 2s 20s 1, moveHorizontal 16s 21.5s 1;
  animation-fill-mode: forwards;
}
</style>
