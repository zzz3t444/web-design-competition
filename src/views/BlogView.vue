<script setup>
import "../assets/css/responsive.css";
import "../views/style/BlogView.css";
import GithubIco from "../assets/ico/githubIco.vue";
import facebookIco from "../assets/ico/facebookIco.vue";
import Insta from "../assets/ico/insta.vue";
import pcIco from "../assets/ico/pcIco.vue";
import twitterico from "../assets/ico/twitterico.vue";

import messageIco from "@/assets/ico/messageIco.vue";
import locationIco from "../assets/ico/locationIco.vue";

//import icons 
import vue from '../components/ico/vue.vue'
import spring from '../components/ico/spring.vue'
import nest from '../components/ico/nest.vue'
import Ruby from '../components/ico/ruby.vue'
import angular from '../components/ico/angular.vue'
import react from '../components/ico/react.vue'
import express from '../components/ico/express.vue'
import next from '../components/ico/next.vue'
import svelte from '../components/ico/svelte.vue'
import vite from '../components/ico/vite.vue'
import django from '../components/ico/django.vue'
import laravel from '../components/ico/laravel.vue'
</script>

<template>
  <div class="ClasAll">
    <section id="backToUp">
      <div class="xl:mt-20">
        <div class="xl:container m-auto px-6 text-gray-600 md:px-12">
          <div
            class="dark:lg:bg-darker rounded-[4rem] md:flex flex-row-reverse md:gap-6 justify-between mx-auto md:space-y-0 lg:items-center"
          >
            <div class="md:5/12 lg:w-1/2 md:block lg:block xl:block hidden">
              <img
                src="../assets/img/staravatar.png"
                class="mx-auto animate-up-down duration-300"
                alt="image"
                loading="lazy"
                width="500px"
                height=""
              />
            </div>
            <div class="md:7/12 mt-10 xl:mt-0 lg:w-2/3">
              <h2
                class="text-2xl sm:text-3xl font-medium text-gray-900 md:text-4xl lg:text-5xl text-start xl:text-[50px] xl:text-start sm:text-center xl:leading-[53px] leading-tight dark:text-gray-200"
              >
                Kami menjaga ekosistem pengembangan setiap framework yang kami jalankan.
              </h2>
              <p
                class="xl:mt-8 mt-4 text-gray-600 leading-6 text-start xl:text-start xl:text-lg xl:leading-7 text-sm dark:text-gray-300"
              >
                Komunitas ini mendorong kolaborasi antara pengembang. Melalui diskusi, forum, atau
                platform kolaborasi lainnya, anggota dapat berbagi pengalaman, solusi, dan ide untuk
                meningkatkan penggunaan framework yang mereka kuasai.
              </p>
              <div class="divide-y space-y-4 divide-gray-100 dark:divide-gray-800">
                <div class="xl:mt-20 mt-6 flex gap-4 md:items-center hover:scale-105 duration-100">
                  <div
                    class="w-12 h-12 hidden xl:flex gap-4 rounded-full bg-indigo-100 dark:bg-indigo-900/20"
                  >
                    <messageIco />
                  </div>
                  <div class="w-5/6">
                    <h3 class="font-semibold text-lg text-gray-700 dark:text-indigo-300">Chat</h3>
                    <p class="text-gray-500 mt-3 text-sm dark:text-gray-400">
                      Pelajari ekosistem kami dengan bertanya di forum kami.
                    </p>
                  </div>
                </div>
                <div class="pt-4 flex gap-4 md:items-center hover:scale-105 duration-100">
                  <div
                    class="w-12 h-12 hidden xl:flex gap-4 rounded-full bg-teal-100 dark:bg-teal-900/20"
                  >
                    <locationIco />
                  </div>
                  <div class="w-5/6">
                    <h3 class="font-semibold text-lg text-gray-700 dark:text-teal-300">Location</h3>
                    <p class="text-gray-500 mt-3 text-sm dark:text-gray-400">
                      kami menyediakan lokasi kantor Nusantara Developer untuk anda
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="xl:mt-28 mt-10">
      <div class="ClassName xl:p-0 p-5">
        <h3 class="xl:text-4xl text-2xl leading-8 text-start dark:text-gray-200">
          kami bangga dengan <span class="dark:text-blue-400 font-semibold">integration</span> dan
          existing <span class="dark:text-sky-400 font-semibold">ecosystem</span>.
        </h3>
        <p class="dark:text-gray-300 xl:text-lg xl:w-1/3 xl:leading-7 xl:mt-8 mt-2">
          Berdasarkan Integrasi dan Ecosystem Yang kami pakai ada beberapa hal penting yang kami
          Perhatikan.
        </p>
      </div>
      <div class="border-t border-gray-300 dark:border-gray-700 mt-5 xl:mt-12 h-5"></div>
      <div class="ClassName xl:mt-10">
        <h3 class="ClassName xl:text-3xl p-5 xl:p-0 dark:text-gray-200 font-semibold">
          UI an DB framework
        </h3>
      </div>
      <div class="flex flex-wrap justify-center mt-2 xl:mt-14">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
               <vue/>   
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Vue JS</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Dalam Ecosystem Vue JS kami, setiap anggota komunitas memiliki akses ke
                  pengetahuan dan keterampilan yang mendalam dalam pengerjaan frontend yang dinamis
                  dan responsif. Dari pengalaman praktis hingga wawasan mendalam, komunitas kami
                  membentuk fondasi kuat bagi para pengembang Vue JS untuk terus tumbuh dan
                  berkolaborasi.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
               <spring/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Spring</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Anggota komunitas kami tidak hanya terampil dalam menggunakan Framework Spring,
                  tetapi juga mampu mengintegrasikan berbagai teknologi terkini yang mendukung
                  ekosistem pengerjaan kami. Kerjasama antaranggota yang solid, pertukaran
                  pengetahuan yang aktif, dan komitmen terhadap kualitas tinggi adalah inti dari
                  budaya kami.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl xl:h-[280px] shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
                <nest/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Nest JS</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Kolaborasi Efektif: Proyek-proyek yang kami tangani dikerjakan secara kolaboratif,
                  memanfaatkan kekuatan individu-individu yang memiliki pemahaman mendalam tentang
                  Nest JS, sehingga menciptakan solusi yang kokoh dan inovatif.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
                <Ruby/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Ruby</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Ecosystem pengerjaan Framework di komunitas Nusantara Developer tidak hanya
                  sekadar sekelompok pengembang, tetapi sebuah kolaborasi harmonis di antara para
                  ahli yang mahir dalam berbagai bidang. Dalam dunia pengerjaan perangkat lunak,
                  Ruby menjadi fondasi yang kuat untuk menghasilkan solusi yang inovatif dan
                  efisien.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
                <angular/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Angular</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Forum diskusi eksklusif kami menyediakan platform bagi anggota untuk berbagi
                  pengalaman, memecahkan masalah, dan bertanya tentang pengembangan dengan Angular.
                  Dengan demikian, membangun fondasi pengetahuan yang kokoh untuk membantu anggota
                  mencapai keberhasilan dalam proyek-proyek mereka.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4">
          <div
            class="rounded-3xl shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800 hover:scale-105 duration-100"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
               <react/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">React</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Salah satu elemen kunci dalam Ecosystem kami adalah penggunaan React sebagai
                  framework utama. React memberikan fondasi yang kuat untuk pengembangan antarmuka
                  pengguna yang dinamis dan responsif. Dengan pendekatan komponen yang modular,
                  React memungkinkan kami untuk membangun aplikasi yang skalabel dan mudah
                  dipelihara.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl xl:h-[307px] shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
               <express/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Express JS</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Salah satu komponen kunci dalam Ecosystem kami adalah penggunaan Express JS,
                  sebuah framework yang ringan namun kuat, dirancang khusus untuk membangun aplikasi
                  web dengan cepat dan mudah. Kami memahami kebutuhan akan kecepatan dan
                  fleksibilitas, dan Express JS menjadi pilihan utama untuk memenuhi tuntutan
                  tersebut.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
                <next/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Next JS</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Dengan keunggulan ini, komunitas kami berhasil menciptakan lingkungan yang
                  memungkinkan para pengembang untuk berkembang dan berinovasi secara efektif,
                  menciptakan solusi yang tangguh dan efisien menggunakan Next.js. Ini adalah
                  ekosistem yang dinamis, kolaboratif, dan selalu berkembang untuk mengakomodasi
                  kebutuhan pengembangan web yang terus berkembang.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="mt-44">
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl xl:h-[307px] shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
                <svelte/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Svelte</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Secara keseluruhan, Ecosystem pengerjaan Framework Svelte di komunitas kami
                  menciptakan lingkungan yang mendukung, kolaboratif, dan inovatif. Kami yakin bahwa
                  dengan fondasi yang kokoh ini, kami dapat terus menghasilkan solusi-solusi web
                  yang canggih dan memuaskan kebutuhan pengguna dan industri secara efektif.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
               <vite/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Vite</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Ecosystem pengerjaan proyek dengan Vite di komunitas kami melibatkan kolaborasi
                  yang harmonis antara para pengembang, desainer, dan pemangku kepentingan lainnya.
                  Framework ini memberikan kecepatan dan kelincahan yang luar biasa dalam
                  pengembangan, memungkinkan tim untuk fokus pada kreativitas dan inovasi tanpa
                  terbebani oleh proses yang lambat.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap justify-center xl:mt-10">
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl xl:h-[300px] shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
                <django/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Django</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Komunitas kami telah mengembangkan berbagai modul dan library kustom yang dapat
                  mempercepat dan menyederhanakan proses pengembangan menggunakan Django.
                  Modul-modul ini dirancang untuk mengatasi kebutuhan umum dan memastikan
                  konsistensi dalam setiap proyek.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-full sm:w-1/2 lg:w-2/4 p-4 hover:scale-105 duration-100">
          <div
            class="rounded-3xl xl:h-[300px] shadow-md dark:border bg-[#f4f8fb] dark:bg-[#1c1c2e] hover:dark:bg-[#1c1c2e] dark:border-gray-800"
          >
            <div class="ClassName flex gap-10 p-7">
              <div class="ClassSVG">
                <laravel/>
              </div>
              <div class="ClassDesk">
                <h3 class="dark:text-gray-200 xl:text-2xl font-semibold">Laravel</h3>
                <p class="mt-5 dark:text-gray-300 leading-7 mb-7">
                  Di balik setiap framework yang sukses adalah komunitas yang solid. Komunitas
                  Laravel kami aktif, ramah, dan selalu bersedia berbagi pengetahuan. Dari forum
                  online hingga pertemuan lokal, anggota komunitas saling mendukung dan bertukar
                  ide, membentuk landasan kuat bagi pertumbuhan dan inovasi.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="ClassName xl:mt-44">
      <div class="container px-6 py-10 mx-auto">
        <h1
          class="text-2xl font-semibold text-gray-800 capitalize leading-8 lg:text-3xl dark:text-white"
        >
          Kami tidak Melupakan sisi lain <span class="dark:text-red-500">hal penting</span>🔍
        </h1>
        <p
          class="mt-4 text-gray-500 xl:mt-5 leading-8 dark:text-gray-300 xl:text-lg xl:leading-7 xl:w-2/6"
        >
          ekosistem kami tidak hanya sekedartr membuat website alakadarnya, tetapi memperhatikan
          pertimbangan lainnya
        </p>

        <div
          class="grid grid-cols-1 gap-8 mt-6 xl:mt-10 xl:gap-[40px] md:grid-cols-2 xl:grid-cols-3"
        >
          <div
            class="space-y-3 xl:h-[400px] p-10 rounded-3xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e] shadow-xl"
          >
            <span
              class="inline-block p-3 text-gray-200 rounded-full dark:text-white bg-red-500 shadow-red-500"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"
                />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">
              pencatatan Pengerjaan
            </h1>
            <p class="text-gray-500 text-sm leading-6 dark:text-gray-300">
              Dalam komunitas kami, pencatatan pengerjaan framework menjadi landasan yang tidak
              tergantikan untuk membangun ekosistem yang kokoh. Setiap langkah dan perkembangan
              dalam pengerjaan framework dicatat secara teliti, mencerminkan dedikasi dan kolaborasi
              dari setiap anggota komunitas.
            </p>
          </div>

          <div
            class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e] shadow-xl"
          >
            <span class="inline-block p-3 text-gray-200 rounded-full dark:text-white bg-blue-500">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"
                />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">
              Pembenaan Data
            </h1>
            <p class="text-gray-500 text-sm leading-6 dark:text-gray-300">
              Framework Pembenaan Data kami menekankan pentingnya pemeliharaan kualitas data,
              keamanan, dan kepatuhan. Dengan pendekatan ini, kami memastikan bahwa data yang
              dihasilkan dan digunakan oleh komunitas ini dapat diandalkan, akurat, dan sesuai
              dengan standar etika serta peraturan yang berlaku.
            </p>
          </div>

          <div
            class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e] shadow-xl"
          >
            <span class="inline-block p-3 text-gray-200 rounded-full dark:text-white bg-orange-500">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"
                />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">
              Performa Framework
            </h1>
            <p class="text-gray-500 text-sm leading-6 dark:text-gray-300">
              Kinerja framework kami tercermin dalam kemampuannya untuk menyelaraskan berbagai aspek
              kegiatan komunitas. Mulai dari manajemen proyek hingga kolaborasi antaranggota,
              framework ini memberikan fondasi yang kokoh bagi inovasi dan pencapaian bersama.
            </p>
          </div>

          <div
            class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e] shadow-xl"
          >
            <span class="inline-block p-3 text-gray-200 rounded-full dark:text-white bg-green-500">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z"
                />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">
              elegant Dark Mode
            </h1>
            <p class="text-gray-500 text-sm leading-6 dark:text-gray-300">
              Dengan Dark Mode, pengguna dapat dengan mudah mengakses platform kami tanpa mengalami
              kelelahan mata, terutama saat berinteraksi di lingkungan yang minim cahaya. Kami
              percaya bahwa memberikan opsi tampilan yang ramah mata tidak hanya meningkatkan
              estetika, tetapi juga memperluas aksesibilitas bagi semua anggota komunitas kami.
            </p>
          </div>

          <div
            class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e] shadow-xl"
          >
            <span class="inline-block p-3 text-gray-200 rounded-full dark:text-white bg-purple-500">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M11 4a2 2 0 114 0v1a1 1 0 001 1h3a1 1 0 011 1v3a1 1 0 01-1 1h-1a2 2 0 100 4h1a1 1 0 011 1v3a1 1 0 01-1 1h-3a1 1 0 01-1-1v-1a2 2 0 10-4 0v1a1 1 0 01-1 1H7a1 1 0 01-1-1v-3a1 1 0 00-1-1H4a2 2 0 110-4h1a1 1 0 001-1V7a1 1 0 011-1h3a1 1 0 001-1V4z"
                />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">
              Customasi Mudah
            </h1>
            <p class="text-gray-500 text-sm leading-6 dark:text-gray-300">
              Dengan alat customisasi yang intuitif dan fleksibel, Nusantara Developer memberikan
              Anda kekuatan untuk membuat lingkungan pengembangan yang sesuai dengan keinginan dan
              gaya Anda. Baik Anda seorang pemula yang baru memulai atau seorang ahli, setiap
              anggota merasa nyaman dan produktif.
            </p>
          </div>

          <div
            class="space-y-3 p-10 rounded-3xl hover:scale-105 duration-100 bg-[#f4f8fb] dark:bg-[#1c1c2e] shadow-xl"
          >
            <span class="inline-block p-3 text-gray-200 rounded-full dark:text-white bg-[#2cbcad]">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"
                />
              </svg>
            </span>
            <h1 class="text-xl font-semibold text-gray-700 capitalize dark:text-white">
              Design Bersih & Rapi
            </h1>
            <p class="text-gray-500 text-sm leading-6 dark:text-gray-300">
              Di tengah-tengah atmosfer kolaboratif kami, kami memprioritaskan desain yang bersifat
              inklusif dan ramah pengguna. Melalui proses desain partisipatif, setiap anggota
              komunitas memiliki kesempatan untuk memberikan kontribusi dan ide-ide kreatif mereka.
              Dengan demikian, kami menciptakan sebuah lingkungan di mana keberagaman dihargai, dan
              setiap individu merasa diakui.
            </p>
          </div>
        </div>
      </div>
    </section>

    <div class="ClassName p-5">
      <div class="p-6 py-12 xl:mt-40 rounded-xl xl:shadow-md dark:bg-[#1c1c2e]">
        <div class="container mx-auto">
          <div class="flex flex-col lg:flex-row items-center justify-between">
            <h2 class="text-center text-6xl dark:text-gray-200 tracki font-bold">
              Up to <br class="sm:hidden" />Popular
            </h2>
            <div class="space-x-2 text-center mt-3 xl:mt-0 dark:text-gray-200 py-2 lg:py-0">
              <span>Our community does not exist Payment</span>
              <span class="font-bold text-lg">Nusantara Developer</span>
            </div>
            <a
              href="#backToUp"
              rel="noreferrer noopener"
              class="px-5 mt-7 xl:mt-0 lg:mt-0 py-3 rounded-md dark:text-gray-200 block dark:bg-[#14141f] hover:scale-95 duration-100"
              >Back to Up</a
            >
          </div>
        </div>
      </div>
    </div>

    <section>
      <div class="viewFooter mt-10 xl:mt-52">
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
            <a class="dark:text-black text-black text-sm text-center font-medium" href="#backToUp"
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
