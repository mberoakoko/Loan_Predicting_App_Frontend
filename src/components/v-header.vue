<template>
    <header class="my_header">
        <div class="logo">I am a logo</div>
        <div class="hamburger" @click="openNav">
            <img src="../../src/assets/photos/hamburger-icon.svg" alt="hamburger_icon">
        </div>
        <div class="sidenav">
            <a href="#" class="close_btn" @click="closeNav">&times;</a>
            <a href="#">Services</a>
            <a href="#">Clients</a>
            <a href="#">Services</a>
            <a href="#">Contacts</a>

        </div>
    </header>
</template>

<script>
import {defineComponent} from "vue"
export default defineComponent({
    name: "V_header",
    methods: {
        openNav(){
            document.querySelector(".sidenav").style.width = "250px"
        },
        closeNav(){
            document.querySelector(".sidenav").style.width = "0"
        }
    }
})


</script>

<style lang="scss" scoped>
    .my_header{
        width: 100%;
        height: 65px;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        background: #fffcfc;
        box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
        transition: all 0.3s cubic-bezier(.25,.8,.25,1);
        position: fixed;
        z-index: 132;
        &:hover{
            box-shadow: 0 7px 14px rgba(0,0,0,0.13), 0 5px 5px rgba(0,0,0,0.22);
        }
        .logo{

        }
        .hamburger{
            width: 45px;
            height: 45px;
            img{
                height: 100%;
                width: 100%;
                transition: 0.5s;
                &:hover{
                    filter: invert(52%) sepia(1%) saturate(0%) hue-rotate(113deg) brightness(96%) contrast(100%);
                }
            }
        }
        .sidenav{
            position: fixed;
            width: 0;
            height: 100vh;
            z-index: 500;
            background-color: black;
            left: 0;
            top: 0;
            overflow-x: hidden;
            padding-top: 60px;
            transition: 0.5s;
            a{
                padding: 8px 8px 8px 32px;
                text-decoration: none;
                font-size: 25px;
                color: #818181;
                display: block;
                transition: 0.3s;
                &:hover{
                    color: #f1f1f1;
                }
            }
            .close_btn{
                position: absolute;
                top: 0;
                right: 25px;
                font-size: 36px;
                margin-left: 50px;
            }
            @media screen and (max-height: 450px) {
                .sidenav {padding-top: 15px;}
                .sidenav a {font-size: 18px;}
            }
        }
    }
</style>
