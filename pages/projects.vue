<template>

    <span class="text-[4rem]">
        <span class="font-bold"> Our current </span>
        <span class="font-bold brand-gradient"> projects. </span>
    </span>

    <projectContainer>

        <span class="flex items-center gap-4">

            <span class="text-5xl font-bold"> OpenCane </span>

            <img class="h-12 bg-white rounded-xl p-1" src="https://cdn-icons-png.flaticon.com/512/3550/3550902.png">

        </span>

        <div class="text-2xl">

            This is a mod that adds an interesting powdery item, along with other interesting natural products to Minecraft. It also adds alcohol and tobacco.

        </div>

        <div class="text-2xl">

            If you want to contribute, check out
            the <a class="underline" href="https://github.com/custardmc/opencane/">Github</a> repository.

        </div>

    </projectContainer>

    <div class="flex flex-row gap-4 flex-wrap">

        <NuxtLink to="https://modrinth.com/project/opencane/"> <user> Modrinth <LucideBox /> </user> </NuxtLink>

    </div>

    <projectContainer>

        <span class="flex items-center gap-4">

            <span class="text-5xl font-bold"> RPConfig </span>

            <img class="h-12 bg-white rounded-xl p-1" src="https://cdn-icons-png.flaticon.com/512/3550/3550902.png">

        </span>

        <div class="text-2xl">

            A simple mod providing Configuration support for Resource Packs.

        </div>

    </projectContainer>

    <div class="flex flex-row gap-4 flex-wrap">

        <NuxtLink to="https://modrinth.com/project/rpopts/"> <user> Modrinth <LucideBox /> </user> </NuxtLink>

    </div>

</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Projects - CustardMC',
  description: "Projects created by the CustardMC Project.",
  ogImage: "~/assets/img/icon512.png",
})
</script>