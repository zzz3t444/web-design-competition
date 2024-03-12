<template>
  <div class="dm_sans width">
    <div class="parallax">
      <h1 class="text-2xl font-bold text-gray-100">Colaboration Program</h1>
    </div>
    <div class="content-text">
      <p
        class="text-gray-300 max-desk-parallax1 text-start text-sm xl:text-sm xl:leading-7 leading-6"
      >
        Foto di atas ini , menunjukan kami dapat Berkolaborasi antar sesama Programmer dan kami
        sangat Solid.
      </p>
    </div>
  </div>
</template>

<script>
window.addEventListener("scroll", function () {
  let offset = window.pageYOffset;
  let parallax = document.querySelector(".parallax");
  parallax.style.backgroundPositionY = offset * 0.7 + "px";
});
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;0,9..40,700;0,9..40,800;0,9..40,900;0,9..40,1000;1,9..40,300;1,9..40,400;1,9..40,500;1,9..40,600;1,9..40,700;1,9..40,800;1,9..40,900;1,9..40,1000&display=swap");
.dm_sans {
  font-family: "DM Sans", sans-serif;
}

.parallax {
  border-top-right-radius: 20px;
  border-top-left-radius: 20px;
  background-image: url("../assets/img/playground.png");
  background-size: cover;
  background-position: center;
  height: 350px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
}

.content-text {
  padding: 50px;
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
  text-align: center;
}

.max-desk-parallax1 {
  max-width: 500px;
}
</style>
