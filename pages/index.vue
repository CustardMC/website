<template>

    <span class="text-[4rem]">
        <span class="font-bold"> This is </span>
        <span class="font-bold brand-gradient"> CustardMC. </span>
    </span>

    <div class="text-2xl">

        We are an organization making <i>silly</i> mods from all flavours.

    </div>

    <div class="text-2xl">

        Feel free to contribute on
        our <a class="underline" href="https://github.com/custardmc">Github</a> repositories.

    </div>

    <span class="text-5xl font-bold"> Developers </span>

    <div class="flex flex-row gap-4 flex-wrap">

        <NuxtLink to="https://blryface.xyz/"> <user> Blurryface <LucideScanFace /> </user> </NuxtLink>

        <NuxtLink to="https://worldwidepixel.ca/"> <user> WorldWidePixel <LucideGlobe /> </user> </NuxtLink>
        
        <NuxtLink to="https://github.com/sakecode/"> <user> Sake <LucideRadar /> </user> </NuxtLink>
        
        <NuxtLink to="https://intergrav.xyz/"> <user> Devin <LucideSnail /> </user> </NuxtLink>

        <NuxtLink to="https://www.youtube.com/channel/UC5njjwz4TCDSNArU2lbhgRg/"> <user> Radiance <LucideSun /> </user> </NuxtLink>

        <NuxtLink to="https://github.com/exhq/"> <user> exhq <LucideAudioWaveform /> </user> </NuxtLink>

        <NuxtLink to="https://rowan.pages.dev/"> <user> Rowan <LucideTreeDeciduous /> </user> </NuxtLink>

        <NuxtLink to="https://callmeecho.dev/"> <user> CallMeEcho <LucideAudioLines /> </user> </NuxtLink>

        <NuxtLink to="https://https://catsta.red/"> <user> TheKodeToad <LucideCode2 /> </user> </NuxtLink>

        <NuxtLink to="https://github.com/yetAnotherEgirl/"> <user> Emily <LucidePersonStanding /> </user> </NuxtLink>

    </div>

</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Home - CustardMC',
  description: "We are an organization making silly mods from all flavours.",
  ogImage: "~/assets/img/icon512.png",
})
</script>
