<template>
    <footer>
        <p style="color: white">I am the footer</p>
    </footer>
</template>

<script>
import {defineComponent} from "vue"
export default defineComponent({
    name: "V_footer"
})
</script>

<style lang="scss" scoped>
    footer{
        position: relative;
        width: 100vw;
        height: 200px;
        background: black;
        transform: translateY(80px);
        left: 0;
        bottom: 0;
        right: 100vw;

    }
</style>
