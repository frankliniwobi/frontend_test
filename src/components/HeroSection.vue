<script setup>
import CatImageOne from './images/CatImageOne.vue'
import CatImageThree from './images/CatImageThree.vue'
import CatImageTwo from './images/CatImageTwo.vue'
</script>

<template>
  <div class="p-0 m-0 mt-3">
    <div class="text-center flex justify-center gap-4 items-center">
      <h1
        class="font-sans inline-flex font-bold text-4xl sm:text-7xl lg:text-8xl leading-1 md:leading-2 text-white"
      >
        We are Pet.
      </h1>

      <div class="flex items-center p-2 h-8 bg-[#3051FF] gap-1 rounded-[16px] text-white">
        <span class="text-sm">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z"
            />
          </svg>
        </span>
        <span class="font-sans font-medium text-xs md:text-xl tracking-tighter text-left"
          >+1 (671) 555-0110</span
        >
      </div>
    </div>

    <p
      class="font-sans font-bold h-[76px] w-full mx-auto mt-2 text-2xl sm:text-4xl lg:text-6xl leading-1 md:leading-2 tracking-tighter text-center text-white"
    >
      Caring Vets, Healthy Pets - Trust Us
    </p>
  </div>

  <div class="flex flex-row flex-wrap justify-center gap-5">
    <div class="flex items-center gap-3 flex-row flex-wrap justify-center relative pb-20">
      <span>
        <CatImageOne />
      </span>
      <div>
        <p class="font-sans text-base font-normal leading-6 text-white text-left">
          Our veterinary clinic is a <br />
          compassionate and skilled facility <br />
          dedicated to providing high-quality <br />
          medical care for pets.
        </p>

        <button
          class="flex items-center justify-around px-2 py-1 mt-2 bg-white text-primary rounded-full"
        >
          <span class="pl-4 font-semibold">Services</span>

          <span class="pl-2 ml-2">
            <svg
              width="40"
              height="40"
              viewBox="0 0 40 40"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect width="40" height="40" rx="20" fill="#183DFF" />
              <path
                d="M15 25L25 15"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M15 15H25V25"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span>
        </button>
      </div>

      <div
        class="absolute left-16px sm:left-0 bottom-0 flex items-center p-3 bg-[#3051FF] gap-1 rounded-[16px] text-white text-base"
      >
        <span class="text-sm">
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M12 2C9.87827 2 7.84344 2.84285 6.34315 4.34315C4.84285 5.84344 4 7.87827 4 10C4 13.0981 6.01574 16.1042 8.22595 18.4373C9.31061 19.5822 10.3987 20.5195 11.2167 21.1708C11.5211 21.4133 11.787 21.6152 12 21.7726C12.213 21.6152 12.4789 21.4133 12.7833 21.1708C13.6013 20.5195 14.6894 19.5822 15.774 18.4373C17.9843 16.1042 20 13.0981 20 10C20 7.87827 19.1571 5.84344 17.6569 4.34315C16.1566 2.84285 14.1217 2 12 2ZM12 23C11.4453 23.8321 11.445 23.8319 11.4448 23.8317L11.4419 23.8298L11.4352 23.8253L11.4123 23.8098C11.3928 23.7966 11.3651 23.7776 11.3296 23.753C11.2585 23.7038 11.1565 23.6321 11.0278 23.5392C10.7705 23.3534 10.4064 23.0822 9.97082 22.7354C9.10133 22.043 7.93939 21.0428 6.77405 19.8127C4.48426 17.3958 2 13.9019 2 10C2 7.34784 3.05357 4.8043 4.92893 2.92893C6.8043 1.05357 9.34784 0 12 0C14.6522 0 17.1957 1.05357 19.0711 2.92893C20.9464 4.8043 22 7.34784 22 10C22 13.9019 19.5157 17.3958 17.226 19.8127C16.0606 21.0428 14.8987 22.043 14.0292 22.7354C13.5936 23.0822 13.2295 23.3534 12.9722 23.5392C12.8435 23.6321 12.7415 23.7038 12.6704 23.753C12.6349 23.7776 12.6072 23.7966 12.5877 23.8098L12.5648 23.8253L12.5581 23.8298L12.556 23.8312C12.5557 23.8314 12.5547 23.8321 12 23ZM12 23L12.5547 23.8321C12.2188 24.056 11.7807 24.0556 11.4448 23.8317L12 23Z"
              fill="white"
            />
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M12 8C10.8954 8 10 8.89543 10 10C10 11.1046 10.8954 12 12 12C13.1046 12 14 11.1046 14 10C14 8.89543 13.1046 8 12 8ZM8 10C8 7.79086 9.79086 6 12 6C14.2091 6 16 7.79086 16 10C16 12.2091 14.2091 14 12 14C9.79086 14 8 12.2091 8 10Z"
              fill="white"
            />
          </svg>
        </span>
        <span class="font-sans font-medium text-base tracking-tighter text-left"
          >2715 Ash Dr. San Jose, South Dakota 83475</span
        >
      </div>
    </div>

    <div class="flex flex-col">
      <div>
        <CatImageTwo />
      </div>
      <div class="text-white">
        Trust us to be your go-to vet <br />
        clinic for all your pet's healthcare <br />
        needs.
      </div>
    </div>

    <div class="flex flex-col">
      <div>
        <CatImageThree />
      </div>
      <div>
        <button
          class="flex items-center justify-around px-2 py-1 mt-2 bg-white text-primary rounded-full"
        >
          <span class="pl-4 font-semibold">Reviews</span>

          <span class="pl-2 ml-2">
            <svg
              width="40"
              height="40"
              viewBox="0 0 40 40"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect width="40" height="40" rx="20" fill="#183DFF" />
              <path
                d="M15 25L25 15"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M15 15H25V25"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </span>
        </button>
      </div>
    </div>
  </div>
</template>
