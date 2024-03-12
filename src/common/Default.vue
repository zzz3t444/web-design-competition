<script>
import { RouterLink, RouterView } from "vue-router";
export default {
  data() {
    return {
      isOpen: false,
    };
  },
  methods: {
    toggleNavbar() {
      this.isOpen = !this.isOpen;
    },
  },
  components: { RouterLink },
};
import "../assets/css/allert.css";
import "../assets/css/responsive.css";
</script>

<template>
  <p class="text-center p-2 allert sm:p-1 md:p-2 lg:p-3 xl:text-base dm_sans text-white">
    Apa yang kami bagikan dalam web ini
    <span class="text-blue-700"
      ><a href="#scrollbawah" class="hover:underline"> Scroll kebawah</a></span
    >
  </p>

  <div class="contain_max max-w-[1270px] mx-auto">
    <nav class="p-5 pt-7">
      <div class="container mx-auto items-center">
        <div class="flex wrapperrast justify-between items-center">
          <a href="#">
            <div class="main-logo flex gap-1 xl:gap-3 items-center">
              <img src="../assets/img/ND.png" class="rounded-full" width="30px" alt="" />
              <h3
                class="text-lg xl:text-2xl tracking-tighter xl:tracking-tighter font-semibold dark:text-white xl:font-bold"
              >
                Nusantara Developer
              </h3>
            </div>
          </a>
          <button @click="toggleNavbar" class="ml-4 md:hidden text-gray-500 focus:outline-none">
            <svg
              v-if="!isOpen"
              class="w-6 h-6"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 384 256"
              fill="none"
            >
              <path
                d="M24 24H360M24 128H360M175 232H360"
                stroke="gray"
                stroke-width="48"
                stroke-miterlimit="10"
                stroke-linecap="round"
              />
            </svg>
            <svg
              v-else
              class="w-6 h-6"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 256 256"
              fill="none"
            >
              <path
                d="M208.49 191.51C210.744 193.764 212.011 196.822 212.011 200.01C212.011 203.198 210.744 206.256 208.49 208.51C206.236 210.764 203.178 212.031 199.99 212.031C196.802 212.031 193.744 210.764 191.49 208.51L128 145L64.49 208.49C62.2357 210.744 59.1781 212.011 55.99 212.011C52.8019 212.011 49.7443 210.744 47.49 208.49C45.2357 206.236 43.9692 203.178 43.9692 199.99C43.9692 196.802 45.2357 193.744 47.49 191.49L111 128L47.51 64.49C45.2557 62.2357 43.9892 59.1781 43.9892 55.99C43.9892 52.8019 45.2557 49.7443 47.51 47.49C49.7643 45.2357 52.8219 43.9692 56.01 43.9692C59.1981 43.9692 62.2557 45.2357 64.51 47.49L128 111L191.51 47.48C193.764 45.2257 196.822 43.9592 200.01 43.9592C203.198 43.9592 206.256 45.2257 208.51 47.48C210.764 49.7343 212.031 52.7919 212.031 55.98C212.031 59.1681 210.764 62.2257 208.51 64.48L145 128L208.49 191.51Z"
                fill="gray"
              />
            </svg>
          </button>

          <div class="hidden_nav">
            <div class="flex space-x-5 text-sm font-medium items-center">
              <RouterLink to="/"
                ><a
                  href="#"
                  class="block dark:text-gray-300 py-2 dark:hover:text-[#4effff] duration-100"
                  >Home</a
                ></RouterLink
              >
              <RouterLink to="/about"
                ><a
                  href="#"
                  class="block dark:text-gray-300 py-2 dark:hover:text-[#4effff] duration-100"
                  >About</a
                ></RouterLink
              >
              <RouterLink to="/services"
                ><a
                  href="#"
                  class="block dark:text-gray-300 py-2 dark:hover:text-[#4effff] duration-100"
                  >Services</a
                ></RouterLink
              >
              <RouterLink to="/contact"
                ><a
                  href="#"
                  class="block dark:text-gray-300 py-2 dark:hover:text-[#4effff] duration-100"
                  >Contact</a
                ></RouterLink
              >
              <RouterLink to="/blog"
                ><a
                  href="#"
                  class="block dark:text-gray-300 py-2 dark:hover:text-[#4effff] duration-100"
                  >Info</a
                ></RouterLink
              >
            </div>
          </div>
        </div>
      </div>
      <div v-if="isOpen" class="container mx-auto md:hidden mt-4">
        <div class="flex-col items-center font-medium">
          <RouterLink to="/"
            ><a
              href="#"
              class="block dark:text-gray-300 py-2 hover:shadow-sm hover:ml-2 dark:hover:text-[#4effff] duration-100"
              >Home</a
            ></RouterLink
          >
          <RouterLink to="/about">
            <a
              href="#"
              class="block dark:text-gray-300 py-2 hover:shadow-sm hover:ml-2 dark:hover:text-[#4effff] duration-100"
              >About</a
            ></RouterLink
          >
          <RouterLink to="/services"
            ><a
              href="#"
              class="block dark:text-gray-300 py-2 hover:shadow-sm hover:ml-2 dark:hover:text-[#4effff] duration-100"
              >Servives</a
            ></RouterLink
          >
          <RouterLink to="/contact">
            <a
              href="#"
              class="block dark:text-gray-300 py-2 hover:shadow-sm hover:ml-2 dark:hover:text-[#4effff] duration-100"
              >Contact</a
            ></RouterLink
          >
          <RouterLink to="/blog"
            ><a
              href="#"
              class="block dark:text-gray-300 py-2 hover:shadow-sm hover:ml-2 dark:hover:text-[#4effff] duration-100"
              >Info</a
            ></RouterLink
          >
        </div>
      </div>
    </nav>

    <section id="scrollbawah">
      <div class="viewRouter">
        <RouterView />
      </div>
    </section>
  </div>
</template>
