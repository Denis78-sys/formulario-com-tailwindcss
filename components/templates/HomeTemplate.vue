<template>
  <div class="home-template">
    <div class="flex justify-center items-center lg:h-screen sm:mt-9 sm:mb-9">
      <div
        class="lg:flex lg:flex-row lg:w-8/12 md:w-11/12 md:flex-row sm:w-10/12 lg:space-y-0 sm:space-y-9 sm:flex-col lg:gap-4 md:gap-9 justify-center items-center"
      >
        <Imagem class="lg:mr-auto" />
        <Formulario class="lg:ml-auto" />
      </div>
    </div>
    <footer class="bg-gray-800 flex p-4 mb-auto justify-center items-center">
      <p class="text-white lg:text-xs sm:text-xs font-thin">
        Desenvolvido por <strong>Denis Marques</strong>
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style scoped></style>
