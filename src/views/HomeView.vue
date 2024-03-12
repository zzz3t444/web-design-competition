<script setup>
// //css file import location
import "../assets/css/keyframes.css";
import "../assets/css/responsive.css";
import "../assets/css/shineText.css";
import "../views/style/HomeView.css";

// //import Ico location
import Profile from "../components/icons/Profile.vue";
import Clock from "../components/icons/Clock.vue";
import htmlIco from "../components/icons/html.vue";
import VueIco from "../components/icons/vueIco.vue";
import SvelteIco from "../components/icons/svelteICo.vue";
import ReactIco from "../components/icons/ReactIco.vue";
import AngularIco from "../components/icons/AngularIco.vue";
import TailwindIco from "../components/icons/tailwindIco.vue";
import BootstrapIco from "../components/icons/bootstrapIco.vue";
import ViteIco from "../components/icons/viteIco.vue";
import NuxtIco from "../components/icons/nuxtIco.vue";
import VuetifyIco from "../components/icons/vuetifyIco.vue";
import PugIco from "../components/icons/pugIco.vue";
import cssIco from "../components/icons/cssIco.vue";
import jsIco from "../components/icons/jsIco.vue";
import nestjsIco from "../components/icons/icoBackend/nestJsIco.vue";
import expressjsIco from "../components/icons/icoBackend/expressjsIco.vue";
import rubyIco from "../components/icons/icoBackend/rubyIco.vue";
import springIco from "../components/icons/icoBackend/springIco.vue";
import nextjsIco from "../components/icons/icoBackend/nextjsIco.vue";
import hapijsIco from "../components/icons/icoBackend/hapijsIco.vue";
import symfonyIco from "../components/icons/icoBackend/symfonyIco.vue";
import laravelIco from "../components/icons/icoBackend/laravelIco.vue";
import fastIco from "../components/icons/icoBackend/fastapiIco.vue";
import djangoIco from "../components/icons/icoBackend/djangoIco.vue";
import Lightning from "../components/icons/lightning.vue";
import chat from "../components/icons/chat.vue";
import Insta from "../assets/ico/insta.vue";
import GithubIco from "../assets/ico/githubIco.vue";
import facebookIco from "../assets/ico/facebookIco.vue";
import pcIco from "..//assets/ico/pcIco.vue";
import twitterico from "../assets/ico/twitterico.vue";
import FacebookCompany from "../assets/ico/facebookCompany.vue";
import digitalOcean from "../assets/ico/digitalOcean.vue";
import amazonCompany from "../assets/ico/amazonCompany.vue";
import teslaCompany from "../assets/ico/teslaCompany.vue";
import adobeCompany from "../assets/ico/adobeCompany.vue";
import searchico from "../assets/ico/searchico.vue";
import checklistico from '../assets/ico/checklistico.vue'

// //CONTENT import location
import paralax1 from "../content/paralax1.vue";
import paralax2 from "../content/paralax2.vue";
import contentBlur from "../content/contentBlur.vue";
import GalleryGrid from "../content/GalleryGrid.vue";
</script>

<template>
  <section id="header-home">
    <!-- Hero -->
    <div class="ClassName">
      <section class="py-12 overflow-hidden sm:pb-16 lg:pb-20 xl:pb-24">
        <div class="px-4 mx-auto relativea sm:px-6 lg:px-8 max-w-7xl">
          <div class="grid items-center grid-cols-1 gap-y-12 lg:grid-cols-2 gap-x-16">
            <div>
              <h1 class="text-4xl font-medium text-black dark:text-gray-100 sm:text-5xl lg:text-6xl xl:leading-tight xl:text-[55px]">Sambungkan Peluang anda Bersama Nusantara Developer</h1>
              <p class="mt-4 xl:text-lg font-normal dark:text-gray-400 sm:mt-8">tunjukan peluang anda di komunitas kami. kembangkan diri anda menjadi lebih <span class="dark:text-gray-100  font-medium">produktif</span> dan <span class="dark:text-gray-100 font-medium">kreatif</span> dalam bidang dunia digital. kami akan selalu tersedia untuk anda</p>

              <form action="#" method="POST" class="relative mt-8 rounded-full sm:mt-12">
                <div class="relative">
                  <div class="absolute rounded-full -inset-px bg-gradient-to-r from-cyan-500 to-purple-500"></div>
                  <div class="relative">
                    <div class="absolute inset-y-0 left-0 flex items-center pl-6">
                      <searchico />
                    </div>
                    <input type="email" name="" id="" placeholder="Explore Our Community." class="block w-full py-4 pr-6 text-white placeholder-gray-500 bg-black border border-transparent rounded-full pl-14 sm:py-5 focus:border-transparent focus:ring-0" />
                  </div>
                </div>
                <div class="sm:absolute flex sm:right-1.5 sm:inset-y-1.5 mt-4 sm:mt-0">
                  <button type="submit" class="inline-flex items-center justify-center w-full px-5 py-5 text-sm font-semibold tracking-widest text-black uppercase transition-all rounded-full bg-[#51e6e6] hover:bg-[#4effff] hover:scale-95 duration-300 sm:w-auto sm:py-3">
                    <a href="#gallery-grid"> Find A Developer </a>
                  </button>
                </div>
              </form>
              <div class="mt-8 sm:mt-12">
                <p class="text-lg font-normal dark:text-white">Trusted by 1000 users</p>
              </div>
            </div>

            <div class="relative">
              <img class="relative w-full hidden lg:block xl:block max-w-md mx-auto animate-up-down duration-500" src="../assets/img/avatar.png" alt="" />
            </div>
          </div>
        </div>
      </section>
    </div>
    <!-- End Hero -->
  </section>

  <div id="gallery-grid" class="ClassName xl:p-0">
    <div class="flex flex-col md:flex-row lg:flex-row xl:flex justify-around gap-2 items-center xl:p-3 md:p-16 dark:border-gray-800 bg-[#f4f8fb] dark:bg-[#1c1c2e] rounded-3xl">
      <div class="galleryGrid xl:p-5 xl:pb-10 p-0">
        <GalleryGrid />
      </div>
      <section class="py-12 sm:py-16 lg:pt-20 lg:pb-20">
        <div class="px-4 mx-auto sm:px-6">
          <div class="grid grid-cols-1 gap-y-8 lg:items-center lg:grid-cols-2 sm:gap-y-20">
            <div class="text-center xl:col-span-2 lg:text-left md:px-16 lg:px-0">
              <div class="max-w-sm mx-auto sm:max-w-md md:max-w-full">
                <h1 class="text-4xl font-medium leading-tight dark:text-gray-200 sm:text-5xl sm:leading-tight lg:text-5xl text-start lg:leading-[60px]">Dapatkan Teman baru dari Komunitas Kami</h1>
                <div class="mt-8 lg:mt-12 lg:flex lg:items-center">
                  <div class="flex xl:justify-center flex-shrink-0 -space-x-4 overflow-hidden lg:justify-start">
                    <img class="inline-block rounded-full w-10 h-10" src="../assets/img/assetpeople/bima.jpg" alt="" />
                    <img class="inline-block rounded-full w-10 h-10" src="../assets/img/assetpeople/dirga.jpg" alt="" />
                    <img class="inline-block rounded-full w-10 h-10" src="../assets/img/assetpeople/gantari.png" alt="" />
                    <img class="inline-block rounded-full w-10 h-10" src="../assets/img/assetpeople/hafidz.jpg" alt="" />
                    <img class="inline-block rounded-full w-10 h-10" src="../assets/img/assetpeople/ian.jpg" alt="" />
                  </div>
                </div>
                <p class="mt-7 text-lg text-start dark:text-gray-400 lg:mt-10">Join dengan <span class="font-bold dark:text-gray-100">1000+ Developers</span> dan mulailah bermimpi dengan teman barumu</p>
              </div>
              <div class="ClassName mt-8">
                <li class="flex items-center gap-3">
                  <checklistico/>
                  <span class="dark:text-gray-400">Pertemanan yang solid</span>
                </li>
                <li class="flex items-center gap-3 mt-2 xl:mt-3">
                  <checklistico/>
                  <span class="dark:text-gray-400">saling membantu</span>
                </li>
              </div>
              <div class="mt-12 hidden xl:flex lg:block xl:gap-5">
                <a href="https://discord.gg/EnTeKrKD" target="_blank" title="" class="inline-flex items-center px-8 py-4 text-sm font-semibold dark:text-gray-200 transition-all border border-cyan-600 hover:border-[#4effff] hover:scale-95 duration-300 rounded-full" role="button"> join NusDev</a>
              </div>
              <div class="ClassName md:hidden lg:hidden xl:hidden grid gap-4 mt-10">
                <button class="p-3 flex w-32 bg-[#51e6e6] hover:bg-[#4effff] hover:scale-95 duration-300 rounded-full">
                  <a class="font-semibold mx-auto text-sm" href="#">join NusDev</a>
                </button>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>

  <section>
    <div class="dark:bg-[#1c1c2e] bg-[#f4f8fb] h-[430px] xl:h-52 rounded-3xl mx-auto mt-7">
      <h3 class="font-medium text-2xl dark:text-gray-500 p-8">Trusted by developers from</h3>
      <div class="flex-row md:flex lg:flex-row xl:flex xl:justify-center xl:gap-28 grid-cols-2 gap-8 md:grid-cols-6 lg:grid-cols-5">
        <div class="flex items-center justify-center col-span-1 md:col-span-2 lg:col-span-1">
          <FacebookCompany />
        </div>

        <div class="flex items-center justify-center col-span-1 md:col-span-2 mt-5 lg:mt-0 xl:mt-0 lg:col-span-1">
          <digitalOcean />
        </div>

        <div class="flex items-center justify-center col-span-1 md:col-span-2 mt-5 lg:mt-0 xl:mt-0 lg:col-span-1">
          <amazonCompany />
        </div>

        <div class="flex items-center justify-center col-span-1 md:col-span-3 mt-8 lg:mt-0 xl:mt-0 lg:col-span-1">
          <teslaCompany />
        </div>

        <div class="flex items-center justify-center col-span-2 md:col-span-3 mt-8 lg:mt-0 xl:mt-0 lg:col-span-1">
          <adobeCompany />
        </div>
      </div>
    </div>
  </section>

  <section id="feature-nusdev">
    <div class="xl:mt-28 mt-7">
      <div class="p-5 xl:p-0">
        <h2 class="text-xl xl:text-4xl font-medium dark:text-gray-100">Kemampuan kami <span class="love">❤️</span> <span class="dark:font-semibold dark:text-[#44dedf]">NusDev</span>.</h2>
        <p class="xl:mt-6 mt-3 text-sm xl:w-1/4 xl:leading-7 dark:text-gray-400 xl:text-lg leading-6">kami Menampilkan Fitur Kami dalam Progres atau <span class="dark:text-gray-100 font-medium">Project Monorepo.</span></p>
      </div>
    </div>

    <div class="flex flex-wrap xl:mt-10 text-black dark:text-white">
      <div class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 p-2">
        <div class="border1 xl:h-80 border hover:scale-105 duration-300 dark:border-gray-800 rounded-3xl p-8 flex-col text-start items-center justify-between hover:border-green-400 hover:shadow-lg hover:shadow-green-600/20 dark:hover:border-green-300/30 bg-[#f4f8fb] dark:bg-[#1c1c2e]">
          <div class="ClassName">
            <Profile />
          </div>
          <h3 class="text-xl mt-3 font-semibold xl:mt-3">Work from home</h3>
          <p class="xl:mt-2 mt-2 dark:text-gray-300 text-md xl:text-md xl:leading-6 leading-6">Ketika kami dirumah kami seringnya berkomunikasi melalui dc and then kami juga melakikukan coding tentunya</p>
        </div>
      </div>

      <div class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 p-2">
        <div class="border2 xl:h-80 rounded-3xl flex items-center justify-center">
          <div class="bord xl:h-80 border hover:scale-105 duration-300 dark:border-gray-800 rounded-3xl p-8 flex-col text-start items-center justify-center hover:border-cyan-400 hover:shadow-lg hover:shadow-cyan-600/20 dark:hover:border-cyan-300/30 bg-[#f4f8fb] dark:bg-[#1c1c2e]">
            <div class="ClassName">
              <Clock />
            </div>
            <h3 class="text-xl mt-3 font-semibold xl:mt-3">24/7 Hours</h3>
            <p class="xl:mt-2 mt-2 dark:text-gray-300 text-md xl:text-md xl:leading-6 leading-6">Kami beroperasi 24/7 untuk meningkatkan kinerja dan pengalaman kami sebagai pengembang, sehingga dapat terus mengasah keterampilan dan pengetahuan.</p>
          </div>
        </div>
      </div>

      <div class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 p-2">
        <div class="border3 xl:h-80 rounded-3xl flex items-center justify-center">
          <div class="bord xl:h-80 border hover:scale-105 duration-300 dark:border-gray-800 rounded-3xl p-8 flex-col text-start items-center justify-center hover:border-red-400 hover:shadow-lg hover:shadow-red-600/20 dark:hover:border-red-300/30 bg-[#f4f8fb] dark:bg-[#1c1c2e]">
            <div class="ClassName">
              <Lightning />
            </div>
            <h3 class="text-xl mt-3 font-semibold xl:mt-3">Cepat tanggap</h3>
            <p class="xl:mt-2 mt-2 dark:text-gray-300 text-md xl:text-md xl:leading-6 leading-6">Kami memiliki kecepatan respons yang tinggi dalam menanggapi permintaan klien karena kami telah dilatih untuk menanggapi dengan efisien.</p>
          </div>
        </div>
      </div>

      <div class="w-full sm:w-1/2 md:w-1/3 lg:w-1/4 p-2">
        <div class="border4 xl:h-80 rounded-3xl flex items-center justify-center">
          <div class="bord xl:h-80 border hover:scale-105 duration-300 dark:border-gray-800 rounded-3xl p-8 flex-col text-start items-center justify-center hover:border-purple-400 hover:shadow-lg hover:shadow-purple-600/20 dark:hover:border-purple-300/30 bg-[#f4f8fb] dark:bg-[#1c1c2e]">
            <chat />
            <h3 class="text-xl mt-3 font-semibold xl:mt-3">Buka Peluang</h3>
            <p class="xl:mt-2 mt-2 dark:text-gray-300 text-md xl:text-md xl:leading-6 leading-6">kita akan selalu menjawab pertanyaan atau pernyataan dari orang lain jika kita memang perlu berkomunikasi.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="button-scroll flex justify-center mt-8">
      <button class="px-6 py-3 bg-[#deeeff] dark:bg-[#192b35] hover:scale-95 duration-300 rounded-full">
        <a class="text-blue-500 font-semibold dark:text-[#46e6e6]" href="#for-marquee">Furthermore, for other things</a>
      </button>
    </div>
  </section>

  <div id="for-marquee">
    <div class="xl:mt-32 mt-14 dm_sans">
      <div class="..">
        <p class="text-[28px] p-3 xl:p-0 xl:text-4xl font-medium leading-8 dark:text-gray-200">Web <span class="dev_txt font-semibold">dev</span> framework <span class="skills_txt font-semibold">skills</span> that we <span class="master_txt font-semibold">master</span></p>
      </div>
    </div>
    <div class="ClassName p-3 xl:p-0">
      <div class="mt-3 xl:mt-16 p-4 xl:p-10 rounded-3xl shadow-xl bg-[#f4f8fb] dark:bg-[#1c1c2e]">
        <div>
          <!-- //marquee icon frontend// -->
          <marquee class="marquee1 rounded-3xl" behavior="" direction="" scrollamount="15">
            <div class="flex items-center gap-6 dark:text-gray-200">
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><htmlIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><VueIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><SvelteIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><ReactIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><AngularIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><TailwindIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><BootstrapIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><ViteIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><NuxtIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><VuetifyIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><PugIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><cssIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><jsIco /></div>
            </div>
          </marquee>
          <!-- //marquee icon backend// -->
          <marquee class="marquee2 mt-5 rounded-3xl" behavior="" direction="right" scrollamount="10">
            <div class="flex items-center gap-6 dark:text-gray-200">
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><nestjsIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><expressjsIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><rubyIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><springIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><nextjsIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><hapijsIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><symfonyIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><laravelIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><fastIco /></div>
              <div class="ico_framework border rounded-full border-gray-300 dark:bg-gray-900 dark:border-gray-900"><djangoIco /></div>
            </div>
          </marquee>
        </div>
        <div class="mt-5 xl:mt-20 flex items-center text-start xl:text-start justify-between">
          <div>
            <h2 class="xl:text-3xl text-2xl dark:text-gray-300 leading-normal font-bold">Awesome Framework Use <span class="dark:shadow-xl">⚙️</span></h2>
            <p class="dark:text-gray-400 mt-4 text-[13px] xl:w-3/5 xl:text-sm font-medium xl:leading-7 leading-6 mb-3 xl:mb-0">Di atas ini adalah semua framework yang kami gunakan ketika kita sedang mengerjakan proejct besar. ada beberapa tools yang memang kami sangat sering Gunakan yaitu Vue JS dan React, untuk backend kami lebih sering menggunakan Nest JS dan Express JS.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- //content profile// -->
  <div class="xl:mt-5">
    <div class="flex flex_responsive_parallax justify-center">
      <div class="p-4 m-2 parallax1 rounded-3xl sm:w-1/2 shadow-xl bg-[#f4f8fb] dark:bg-[#1c1c2e]">
        <paralax1 />
      </div>
      <div class="p-4 m-2 parallax2 rounded-3xl sm:w-1/2 shadow-xl lg:w-full bg-[#f4f8fb] dark:bg-[#1c1c2e]">
        <paralax2 />
      </div>
    </div>

    <div class="content_image_blur mt-10 p-3 lg:p-0 xl:p-0 xl:mt-28">
      <contentBlur />
    </div>

    <section class="xl:mt-32 mt-10 forms">
      <div class="ClassName xl:flex xl:items-center gap-16">
        <div class="dm_sans">
          <div class="ClassName text_main_forms text-start">
            <h3 class="xl:text-4xl text-2xl text-start dark:text-gray-100 font-semibold">You can <span class="text-red-500 red_message_txt">leave</span> a <span>message</span> below</h3>
            <p class="xl:w-3/4 xl:mt-6 mt-4 xl:text-sm text-start xl:leading-7 text-sm dark:text-gray-400 leading-6">Ceritakan apa pun itu. Berikan pesan yang terbaik agar kami semakin bersemangat dalam bekerja.</p>
          </div>
          <div class="items-center justify-center gap-16 mt-14">
            <div class="ClassName">
              <form action="https://api.web3forms.com/submit" method="POST" class="grid gap-4 max-w-8xl mx-auto rounded-lg w-full">
                <input type="hidden" name="access_key" value="3a928331-13f9-4e84-86cf-adb4fb41d57e" />
                <div class="gap-3 flex">
                  <input type="text" name="name" required placeholder="Your Name" class="w-full p-5 rounded-2xl mt-3 shadow-lg dark:shadow-gray-900 focus:outline-none bg-transparent focus:border-blue-500 dark:bg-[#1c1c2e] bg-[#f4f8fb] text-white" />
                  <input type="email" name="email" required placeholder="Your Email" class="w-full p-5 rounded-2xl shadow-lg dark:shadow-gray-900 mt-3 bg-transparent outline-none focus:border-blue-500 dark:bg-[#1c1c2e] bg-[#f4f8fb] text-white" />
                </div>
                <textarea name="message" required placeholder="Your Message" class="w-full px-4 py-4 h-60 rounded-2xl dark:shadow-gray-900 shadow-lg focus:outline-none bg-transparent focus:border-blue-500 dark:bg-[#1c1c2e] bg-[#f4f8fb] text-white"></textarea>
                <button type="submit" class="w-48 mx-auto py-4 px-4 text-sm mt-4 text-black font-semibold rounded-3xl hover:scale-95 bg-[#51e6e6] hover:bg-[#4effff] duration-300 hover:shadow-md hover:dark:shadow-sky-400 focus:outline-none focus:bg-blue-600">Submit Form</button>
              </form>
            </div>
          </div>
        </div>
        <div>
          <img src="../assets/img/phoneframecompres.png" class="rounded-3xl mt-20 hover:scale-105 duration-100 animate-up-down" alt="image form" width="700px" />
        </div>
      </div>
    </section>

    <section>
      <div class="viewFooter mt-10 xl:mt-52">
        <div class="ClassName flex gap-3 justify-center items-center">
          <pcIco />
          <h3 class="text-3xl font-semibold dark:text-gray-200">Nusantara Developer</h3>
        </div>
        <p class="text-center desk_footer xl:mt-5 xl:w-1/3 mx-auto dark:text-gray-400 text-sm leading-6 xl:leading-6">terimakasih telah berkunjung Di Website kami Nusantara Developer. Kami sangat senang Dengan Kehadiran Anda di website ini. semoga menginspirasikan Kalian Semua.</p>
        <div class="ClassName flex justify-center mt-10">
          <button class="p-3 bg-[#51e6e6] hover:bg-[#4effff] duration-300 text-center md:block lg:block xl:block hover:scale-95 hover:shadow-md hover:dark:shadow-sky-300 rounded-full">
            <a class="dark:text-black text-black text-sm text-center font-medium" href="#header-home">back to up</a>
          </button>
        </div>
        <footer class="md:flex md:items-center md:justify-between rounded-lg mt-16 p-4 md:p-6 xl:p-8">
          <ul class="flex group_cr items-center gap-5 flex-wrap md:mb-0">
            <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6">@copyright</a></li>
            <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6">©Nusantara Developer</a></li>
            <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6">ebdtv4@gmail.com</a></li>
            <li><a href="#" class="text-sm font-normal dark:text-gray-200 hover:underline md:mr-6">mhmdzakyadrhm@gmail.com</a></li>
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
