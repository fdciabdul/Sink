<script setup>
import heroImg from '@/assets/images/hero.svg?raw'
import { AreaChart } from 'lucide-vue-next'
import { GitHubIcon } from 'vue3-simple-icons'

const { title, description, github } = useAppConfig()
</script>

<template>
  <main
    class="grid pt-8 pb-8 lg:grid-cols-2 place-items-center md:py-12"
  >
    
    <div class="hidden py-6 md:block">
      <div
        class="w-[512px]"
        v-html="heroImg"
      />
    </div>
  </main>
</template>
