<script setup>
import Graph from "../components/Graph.vue";
import "../assets/css/keyframes.css";
import "../assets/css/responsive.css";
import "../assets/css/shineText.css";
import "../views/style/AboutView.css";

// import Ico
import GithubIco from "../assets/ico/githubIco.vue";
import Github from "../assets/ico/github.vue";
import facebookIco from "../assets/ico/facebookIco.vue";
import Insta from "../assets/ico/insta.vue";
import twitterico from "../assets/ico/twitterico.vue";
import pcIco from "../assets/ico/pcIco.vue";
import discordIco from "../assets/ico/discordIco.vue";
import Discord from "../assets/ico/discord.vue";
import Reddit from "../assets/ico/reddit.vue";
import Zoom from "../assets/ico/zoom.vue";
</script>

<template>
  <div class="shadow_collor">
    <!-- //Graph Peformance// -->
    <section id="header-about">
      <div class="bg_glow_color">
        <div class="ClassName mt-10 xl:mt-28">
          <h2
            class="xl:text-center shine text-[30px] p-3 xl:p-0 font-semibold xl:font-bold xl:text-7xl leading-10 lg:mt-52 dark:text-gray-100"
          >
            Performance Us Nusantara Developer
          </h2>
        </div>
        <div class="ClassName">
          <p
            class="p-3 xl:w-2/4 text-start xl:text-center mx-auto xl:text-[15px] xl:mt-10 xl:leading-7 text-sm leading-6 text-gray-700 dark:text-gray-300"
          >
            Nusantara Developer membawa obrolan dan kolaborasi ke tingkat berikutnya: standup
            harian, check-in tim, survei, pujian, bot pendamping terbaik untuk watercooler virtual
            Anda, motivasi
            <span class="light_lamp">💡</span>
          </p>
        </div>
      </div>
    </section>

    <section class="p-4">
      <div
        class="flex flex-col justify-between xl:p-16 rounded-3xl items-center sm:flex-row xl:mt-16 xl:gap-10 shadow-xl bg-[#f4f8fb] dark:bg-[#1c1c2e]"
      >
        <div class="xl:p-4 w-full sm:w-1/2 rounded-2xl">
          <div class="for_import p-3 xl:p-0">
            <Graph />
          </div>
        </div>
        <div class="p-3 w-full xl:mt-1 sm:w-1/2">
          <p class="text-orange-400 xl:text-base text-sm">Management System</p>
          <h3 class="text-2xl xl:text-5xl font-medium mt-4 leading-tight xl:leading-tight">
            Kelola semua System dan Kesempurnaan Data
          </h3>
          <p
            class="dark:text-gray-300 text-sm xl:text-base xl:leading-6 xl:mt-5 mt-4 xl:p-0 leading-6"
          >
            Kami akan selalu menjaga kesetabilan dan Kesempurnaan Data alam suatu Hal Project yang
            kami buat.kami juga bersedia untuk membantu kesetabilan dan Kesempurnaan dari Semua yang
            berkonstribusi kepada Kami
          </p>
          <p class="dark:text-gray-300 xl:mt-9 mt-3 text-sm xl:text-base font-bold leading-8">
            Rating Kami Untuk kalian Semua
          </p>
          <div class="items-center flex-col sm:flex-row md:flex-col mb-8 lg:mb-0 xl:mb-0 lg:flex-row mt-8 xl:mt-4">
            <a
              href="#grid-github"
              class="bg-[#51e6e6] hover:bg-[#4effff] duration-300 px-8 lg:px-0 xl:px-0  md:block lg:block xl:block mb-8 items-center text-center xl:mb-0 dark:text-black xl:w-60 text-black font-medium p-3 hover:shadow-md hover:shadow-sky-400 rounded-full hover:scale-95"
              >Read More</a
            >
          </div>
        </div>
      </div>
    </section>

    <section id="grid-github">
      <div class="ClassName xl:mt-28 mt-5 grid_github p-2 rounded-3xl">
        <div class="flex flex-wrap items-center justify-between">
          <div class="w-full md:w-1/2 p-4">
            <div class="p-1 rounded center_txt">
              <h4
                class="text-xl xl:text-3xl xl:leading-snug text-start font-medium xl:w-1/1 leading-normal"
              >
                Kami Berada di keempat Platfrom yang populer di Dunia ini. dan Kami Tersedia
              </h4>
              <p
                class="xl:mt-8 mt-4 dark:text-gray-300 text-start text-sm xl:text-base xl:leading-7 leading-6"
              >
                dengan keempat platform yang kami buat, agar mempermudah Semua Atau Pendatang baru
                untuk Saling Berkomunikasi ataupun Berkosntribusi dengan kami. Kami sangat
                menghargai kedatangan Kalian Semua.
              </p>
            </div>
          </div>
          <div class="w-full md:w-1/2 p-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-6">
              <div class="grid grid-cols-1 gap-6">
                <div
                  class="p-6 rounded-3xl flex gap-3 dark:border dark:border-gray-800 hover:scale-105 shadow-xl duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
                >
                  <Discord />
                  <div>
                    <h4 class="dark:text-gray-300">View Of</h4>
                    <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Discord Server</h4>
                  </div>
                </div>
                <div
                  class="p-6 rounded-3xl flex gap-3 dark:border dark:border-gray-800 hover:scale-105 shadow-xl duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
                >
                  <Github />
                  <div>
                    <h4 class="dark:text-gray-300">View Of</h4>
                    <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Repo Github</h4>
                  </div>
                </div>
              </div>
              <div class="grid grid-cols-1 gap-6">
                <div
                  class="p-6 rounded-3xl flex gap-3 dark:border dark:border-gray-800 hover:scale-105 shadow-xl duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
                >
                  <Reddit />
                  <div>
                    <h4 class="dark:text-gray-300">View Of</h4>
                    <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Reddit</h4>
                  </div>
                </div>
                <div
                  class="p-6 rounded-3xl flex gap-3 dark:border dark:border-gray-800 hover:scale-105 shadow-xl duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
                >
                  <Zoom />
                  <div>
                    <h4 class="dark:text-gray-300">View Of</h4>
                    <h4 class="dark:text-gray-200 font-medium text-lg mt-2">Zoom Server</h4>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="other_gallery_card mt-14 xl:mt-44">
        <h2 class="text-3xl text-center leading-10 font-medium">Tim Utama Nusantara Developer</h2>
        <div class="flex flex-wrap xl:gap-5 mx-auto justify-center mt-10 rounded-3xl">
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/dzaky.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Dzaky Abdurrahman</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Backend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/zet.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Zeeta</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/Keyza.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Keyza Dinaro</h3>
              <p class="mt-3 text-sm dark:text-gray-400">DevOps Games</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/vito.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Vito Elkayis</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Database Analyzer</p>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap mx-auto xl:gap-5 justify-center mt-20 rounded-3xl">
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/celis.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Cellistia Putri</h3>
              <p class="mt-3 text-sm dark:text-gray-400">UI Designer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/josha.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Jauza Saktiawan</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Frontend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/zua.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Lazuardi Diendi</h3>
              <p class="mt-3 text-sm dark:text-gray-400">Backend Developer</p>
            </div>
          </div>
          <div class="w-full sm:w-10 md:w-32 lg:w-40 xl:w-72 p-4 duration-100">
            <img
              class="rounded-full asset_profile"
              src="../assets/img/assetpeople/fael.jpg"
              alt=""
            />
            <div class="text-center mt-5">
              <h3 class="text-2xl font-medium">Rafael Destiano</h3>
              <p class="mt-3 text-sm dark:text-gray-400">UI Designer</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <div class="ClassName flex items-center justify-between mt-5 xl:mt-[450px] p-10">
      <h3 class="text-3xl text-start leading-10 xl:text-4xl font-normal">
        <span class="text-sky-400 font-semibold people_txt_glow">People</span>
        constribution on
        <span class="font-semibold discord_txt_glow text-purple-700">Discord</span>
        server
      </h3>
      <a href="https://discord.gg/gqhSqaDm" target="_blank">
        <div
          class="ClassName xl:flex hidden md:block lg:block items-center p-3 border mt-6 xl:mt-0 dark:border-gray-800 rounded-full dark:bg-gray-800 hover:shadow-2xl duration-100 hover:scale-95"
        >
          <discordIco />
        </div>
      </a>
    </div>
    <section class="p-2 dark:text-gray-200 rounded-3xl shadow-xl bg-[#f4f8fb] dark:bg-[#1c1c2e]">
      <div class="flex coloumn_rate items-center p-10 rounded-3xl">
        <div class="ClassName img">
          <img
            src="../assets/img/discordscreenshot.png"
            class="rounded-3xl hover:scale-105 duration-100"
            width="650px"
            alt=""
          />
        </div>
        <div
          class="container_rate mx-auto grid justify-center grid-cols-2 text-center lg:grid-cols-3"
        >
          <div
            class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100"
          >
            <p class="text-4xl font-bold leadi lg:text-6xl">50+</p>
            <p class="text-sm sm:text-base mt-5">Clients</p>
          </div>
          <div
            class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100"
          >
            <p class="text-4xl font-bold leadi lg:text-6xl">1K</p>
            <p class="text-sm sm:text-base mt-5">Pengikut di social media</p>
          </div>
          <div
            class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100"
          >
            <p class="text-4xl font-bold leadi lg:text-6xl">3</p>
            <p class="text-sm sm:text-base mt-5">Public</p>
          </div>
          <div
            class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100"
          >
            <p class="text-4xl font-bold leadi lg:text-6xl">8</p>
            <p class="text-sm sm:text-base mt-5">Tim Utama</p>
          </div>
          <div
            class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100"
          >
            <p class="text-4xl font-bold leadi lg:text-6xl">24</p>
            <p class="text-sm sm:text-base mt-5">Years of experience</p>
          </div>
          <div
            class="flex flex-col justify-start m-2 lg:m-6 dark:shadow-2xl hover:scale-105 duration-100"
          >
            <p class="text-4xl font-bold leadi lg:text-6xl">5+</p>
            <p class="text-sm sm:text-base mt-5">Workshops</p>
          </div>
        </div>
      </div>
    </section>

    <section class="dark:text-gray-200 mt-12 xl:mt-24">
      <div class="container px-5 mx-auto">
        <div class="flex flex-col text-start w-full mb-5 xl:mb-20">
          <h1 class="xl:text-4xl text-3xl font-medium mb-4 dark:text-gray-200">
            Our Discord Member
          </h1>
          <p class="lg:w-2/6 dark:text-gray-300 leading-7 xl:text-lg xl:leading-6 text-base">
            Kami Menampilkan beberapa member di server Discord Kami. dari sisi Divisi masing masing.
          </p>
        </div>
        <div class="flex flex-wrap -m-2">
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/bima.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">bima Nugroho</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/ronald.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Ronald Alexander</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/denis.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Denis Diananta</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/dirga.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Pratama Dirga</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/syafiq.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Syafiq Alfarensqi</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/galih.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Galih Alfarel</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/gantari.png"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Gantari tjandra</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/hafidz.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Hafidz Aulia</h2>
                <p class="text-gray-400">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/ian.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Ian Rachman</h2>
                <p class="text-gray-500">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/majid.jpg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Abdul Majid</h2>
                <p class="text-gray-500">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/rafa.jpeg"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">Rafa Rajendra</h2>
                <p class="text-gray-500">Member</p>
              </div>
            </div>
          </div>
          <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
            <div
              class="h-full flex items-center dark:border-gray-800 hover:bparent border p-4 rounded-2xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e]"
            >
              <img
                alt="team"
                class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4"
                src="../assets/img/assetpeople/acham.png"
              />
              <div class="flex-grow">
                <h2 class="dark:text-gray-200 title-font font-medium">hidzkul Hisyam</h2>
                <p class="text-gray-500">Member</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="viewFooter mt-10 xl:mt-44">
        <div class="ClassName flex gap-3 justify-center items-center">
          <pcIco />
          <h3 class="text-3xl font-semibold dark:text-gray-200">Nusantara Developer</h3>
        </div>
        <p
          class="text-center desk_footer xl:mt-5 xl:w-1/3 mx-auto dark:text-gray-400 text-sm leading-6 xl:leading-6"
        >
          terimakasih telah berkunjung Di Website kami Nusantara Developer. Kami sangat senang
          Dengan Kehadiran Anda di website ini. semoga menginspirasikan Kalian Semua.
        </p>
        <div class="ClassName flex justify-center mt-10">
          <button
            class="p-3 bg-[#51e6e6] hover:bg-[#4effff] duration-300 text-center md:block lg:block xl:block hover:scale-95 hover:shadow-md hover:dark:shadow-sky-300 rounded-full"
          >
            <a
              class="dark:text-black text-black text-sm text-center font-medium"
              href="#header-about"
              >back to up</a
            >
          </button>
        </div>
        <footer
          class="md:flex md:items-center md:justify-between rounded-lg mt-16 p-4 md:p-6 xl:p-8"
        >
          <ul class="flex group_cr items-center gap-5 flex-wrap md:mb-0">
            <li>
              <a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6"
                >@copyright</a
              >
            </li>
            <li>
              <a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6"
                >©Nusantara Developer</a
              >
            </li>
            <li>
              <a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6"
                >ebdtv4@gmail.com</a
              >
            </li>
            <li>
              <a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6"
                >mhmdzakyadrhm@gmail.com</a
              >
            </li>
          </ul>
          <div class="flex space-x-6 ico_footer justify-center">
            <facebookIco />
            <Insta />
            <twitterico />
            <GithubIco />
          </div>
        </footer>
      </div>
    </section>
  </div>
</template>
