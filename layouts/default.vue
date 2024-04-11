<template>

    <div class="flex justify-center flex-col p-6 gap-8">

      <navBar />

      <div class="m-[5%] gap-8 flex-col flex">
        <slot />

      </div>

      <pageFooter />

    </div>

</template>

<style>

@import url(https://fonts.bunny.net/css?family=inter:100,200,300,400,500,600,700,800,900);

:root {
  font-family: Inter, Helvetica, sans-serif;
  --brand-colour: #e6ffff;
}

.brand-gradient {
    background: linear-gradient(90deg, rgb(0, 255, 106) 0%, rgb(6, 176, 255) 100%);
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
}

</style>