<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="formulario lg:w-80">
    <BemVindo />
    <p class="text-white text-gray-400 lg:text-xs sm:text-xs mb-4">
      O Clarity fornece os blocos e componentes necessários para criar um
      ambiente verdadeiramente site profissional.
    </p>
    <button
      class="flex gap-4 justify-center items-center text-white text-xs bg-gray-600 p-2 w-full mb-12 mt-9 rounded-2xl"
    >
      <img src="@/assets/imagens/google.svg" alt="Logo do Google" /> Faça login
      no Google
    </button>
    <form class="space-y-6">
      <div class="space-y-2">
        <label class="text-white text-xs">Endereço de E-mail</label>
        <input
          type="email"
          class="bg-inherit border border-1 border-gray-600 text-white text-sm p-2 w-full rounded-2xl"
          placeholder="exemplo@gmail.com"
        />
      </div>
      <div class="space-y-2">
        <label class="text-white text-xs">Senha</label>
        <input
          type="password"
          class="bg-inherit border border-1 border-gray-600 text-white text-xs p-2 w-full rounded-2xl"
          placeholder="*********"
        />
      </div>
      <div class="mt-9">
        <button
          class="flex gap-4 justify-center items-center text-white text-xs bg-blue-600 p-2 w-24 rounded-2xl"
        >
          Login
        </button>
      </div>
    </form>
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
