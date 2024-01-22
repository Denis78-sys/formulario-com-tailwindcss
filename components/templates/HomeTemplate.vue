<template>
  <div class="home-template">
    <div class="flex justify-center items-center lg:h-screen sm:mt-9 sm:mb-9">
      <div
        class="lg:flex lg:flex-row lg:w-8/12 md:w-11/12 md:flex-row sm:w-10/12 lg:space-y-0 sm:space-y-9 sm:flex-col lg:gap-4 md:gap-9 justify-center items-center"
      >
        <Imagem class="lx:mr-80 lg:mr-20 md:mr-0 sm:mr-0" />
        <Formulario class="" />
      </div>
    </div>
    <footer class="bg-gray-800 mb-0 flex flex-col p-4 mb-auto space-y-1 justify-center items-center">
      <p class="text-white lg:text-xs sm:text-xs font-thin">
        Desenvolvido por <strong>Denis Marques</strong>
      </p>
      <p class="text-white lg:text-xs sm:text-xs font-thin">
       Desenvolvido apenas para estudo - (Formulário sem interação)
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
