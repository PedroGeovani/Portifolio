<script lang="ts">
</script>

<template>
  <section id="about_me" class="snap-end h-screen w-full bg-[#160041] pt-[10rem]">
    <div class="grid grid-cols-2">
      <div>
        <span class="flex text-3xl text-gray-100 font-serif ps-[10rem]"> Sobre mim... </span>
        <img class="scale-x-110" src="../assets//image//ritghbluebotton.svg" />
        <div class="flex text-xl text-gray-100 font-serif text-justify m-4 ps-[10rem]">
          Ola! me chamo Pedro Geovani tenho 40 anos e sou desenvolvedor front-end,
          moro em Fortaleza desde sempre e durante muito tempo fui entusiasta de
          tecnologia, finalmente resolvi mergulhar nesta área. Atualmente sou
          estudante de engenharia no IFCE-Fortaleza, mas tenho uma vasta experiencia
          na área de educação.
        </div>
        <span class="flex text-xl text-gray-100 font-serif justify-end text-justify m-4 ps-[10rem]">Quer saber mais?</span>
        <span class="flex text-xl text-gray-100 font-serif justify-end text-justify m-4 ps-[10rem]">Role a pagina para me conhecer
          mais. </span>
      </div>
      <div>
        <img class="flex w-[25rem] ms-44" src="../assets/image/image.svg" />
      </div>
    </div>
  </section>

  <section id="education" class="h-screen w-full bg-indigo-950 pt-[10rem]">
    <div class="grid grid-cols-2">
      <div>
        <span class="text-3xl text-gray-100 font-serif ps-[10rem]">Formação</span>
        <img src="../assets//image//ritghbluebotton.svg" />
      </div>
      <div>
        <span class="text-3xl text-gray-100 font-serif ps-[10rem]">Competências</span>
        <img class="ps-[2rem]" src="../assets//image//ritghbluebotton.svg" />
      </div>
    </div>

  </section>
  <section id="experiences" class="h-screen w-full bg-indigo-900 p-[10rem]">
    <div>
      <div>
        <span class="text-3xl text-gray-100 font-serif">Experiências</span>
        <img src="../assets//image//ritghbluebotton.svg" />
      </div>
    </div>

  </section>
  <section id="projects" class="h-screen w-full bg-indigo-800 p-[10rem]">
    <div>
      <div>
        <span class="text-3xl text-gray-100 font-serif">Projetos</span>
      </div>
    </div>
  </section>

  <section id="future" class="h-screen w-full bg-indigo-700 p-[10rem]">
<div>
      <div>
        <span class="text-3xl text-gray-100 font-serif">Futuro</span>
      </div>
    </div>
  </section>

  <div
    class="fixed bottom-0 left-0 z-50 w-full h-16 bg-white border-t border-gray-200 dark:bg-gray-700 dark:border-gray-600">
    <div class="grid h-full max-w-4xl  grid-cols-5 mx-auto font-serif">
      <button type="button"
        class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
        <a href="#about_me">
          <span
            class="text-xl text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Sobre
            mim</span>
        </a>
      </button>
      <button type="button"
        class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
        <a href="#education">
          <span
            class="text-xl text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Formação</span>
        </a>
      </button>
      <button type="button"
        class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
        <a href="#experiences">
          <span
            class="text-xl text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Experiências</span>
        </a>
      </button>
      <button type="button"
        class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
        <a href="#projects">
          <span
            class="text-xl text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Projetos</span>
        </a>
      </button>
      <button type="button"
        class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
        <a href="#future">
          <span
            class="text-xl text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Futuro</span>
        </a>
      </button>
    </div>
  </div>
</template>
