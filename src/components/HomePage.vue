<template>
  <div
    class="container flex flex-col flex-wrap items-center px-6 pt-24 mx-auto md:pt-28 md:flex-row"
  >
    <div
      class="flex flex-col justify-center w-full overflow-y-hidden xl:w-2/5 lg:items-start"
    >
      <h1
        class="my-4 text-3xl font-bold leading-tight text-center text-blue-600 md:text-5xl md:text-left slide-in-bottom-h1"
      >
        Make your shop more efficient!
      </h1>
      <p
        class="mb-8 text-base leading-normal text-center md:text-2xl md:text-left slide-in-bottom-subtitle"
      >
        With Shop-testing you can build your own web site thanks to this
        template
      </p>

      <div
        class="flex justify-center w-full pb-24 md:justify-start lg:pb-0 fade-in"
      >
        <LinkBase
          class="inline-block h-10 p-2 text-center text-blue-500 no-underline hover:text-blue-800 hover:text-underline md:h-auto md:p-4"
          href="https://twitter.com"
        >
          <IconBase class="h-6 fill-current" viewBox="0 0 32 32">
            <path
              d="M30.063 7.313c-.813 1.125-1.75 2.125-2.875 2.938v.75c0 1.563-.188 3.125-.688 4.625a15.088 15.088 0 0 1-2.063 4.438c-.875 1.438-2 2.688-3.25 3.813a15.015 15.015 0 0 1-4.625 2.563c-1.813.688-3.75 1-5.75 1-3.25 0-6.188-.875-8.875-2.625.438.063.875.125 1.375.125 2.688 0 5.063-.875 7.188-2.5-1.25 0-2.375-.375-3.375-1.125s-1.688-1.688-2.063-2.875c.438.063.813.125 1.125.125.5 0 1-.063 1.5-.25-1.313-.25-2.438-.938-3.313-1.938a5.673 5.673 0 0 1-1.313-3.688v-.063c.813.438 1.688.688 2.625.688a5.228 5.228 0 0 1-1.875-2c-.5-.875-.688-1.813-.688-2.75 0-1.063.25-2.063.75-2.938 1.438 1.75 3.188 3.188 5.25 4.25s4.313 1.688 6.688 1.813a5.579 5.579 0 0 1 1.5-5.438c1.125-1.125 2.5-1.688 4.125-1.688s3.063.625 4.188 1.813a11.48 11.48 0 0 0 3.688-1.375c-.438 1.375-1.313 2.438-2.563 3.188 1.125-.125 2.188-.438 3.313-.875z"
            ></path>
          </IconBase>
        </LinkBase>
        <LinkBase
          class="inline-block h-10 p-2 text-center text-blue-500 no-underline hover:text-blue-800 hover:text-underline md:h-auto md:p-4"
          href="https://www.facebook.com"
        >
          <IconBase class="h-6 fill-current" viewBox="0 0 32 32">
            <path
              d="M19 6h5V0h-5c-3.86 0-7 3.14-7 7v3H8v6h4v16h6V16h5l1-6h-6V7c0-.542.458-1 1-1z"
            ></path>
          </IconBase>
        </LinkBase>
      </div>
    </div>

    <!--Right Col-->
    <div class="w-full py-6 overflow-y-hidden xl:w-3/5">
      <img
        class="w-5/6 mx-auto lg:mr-0 slide-in-bottom"
        src="../assets/shop-icon.svg"
      />
    </div>

    <div
      class="w-full pt-16 pb-6 text-sm text-center text-gray-500 md:text-left fade-in"
    >
      &copy; Shop-testing 2021
    </div>
  </div>
</template>

<script setup>
import IconBase from "./IconBase.vue";
import LinkBase from "./LinkBase.vue";
</script>