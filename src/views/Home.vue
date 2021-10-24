<template>
  <div class="home" style="display: flex; flex-direction: column ; justify-content: space-between ; height: fit-content">
        <V_header></V_header>
        <main_disp></main_disp>
        <V_footer></V_footer>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
//import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import V_header from "@/components/v-header.vue"
import main_disp from "@/components/main_disp.vue"
import V_footer from "@/components/V_footer.vue"
@Options({
  components: {
    V_header, main_disp, V_footer
  },
})
export default class Home extends Vue {}
</script>
