<template>
    <div class="main_disp">
        <div class="backgroundAction"></div>
        <div class="main_event">
            <img src="../../src/assets/photos/main_background.jpg" alt="main_image">
            <div class="message">
                <h1 style="color:#f16fa9 !important">Loan Predicting App</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Animi beatae blanditiis culpa dolorem doloremque ducimus
                    exercitationem fugit ipsa iste labore libero magni maxime
                    nihil nobis, nulla obcaecati officiis repellat totam.</p>
                <button>Try it out</button>
            </div>
        </div>

    </div>
</template>

<script>
import {defineComponent} from "vue"
export default defineComponent({
    name: "main_disp"
})
</script>

<style lang="scss" scoped>
    .main_disp{
        height: fit-content;
        transform: translateY(60px); // make the sticky work
        position: relative;
        .backgroundAction{
            background-color: #CCAA66;
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='100%25' viewBox='0 0 100 60'%3E%3Cg %3E%3Crect fill='%23CCAA66' width='11' height='11'/%3E%3Crect fill='%23cda864' x='10' width='11' height='11'/%3E%3Crect fill='%23cea762' y='10' width='11' height='11'/%3E%3Crect fill='%23cfa561' x='20' width='11' height='11'/%3E%3Crect fill='%23d0a45f' x='10' y='10' width='11' height='11'/%3E%3Crect fill='%23d1a25d' y='20' width='11' height='11'/%3E%3Crect fill='%23d2a05c' x='30' width='11' height='11'/%3E%3Crect fill='%23d39f5a' x='20' y='10' width='11' height='11'/%3E%3Crect fill='%23d49d59' x='10' y='20' width='11' height='11'/%3E%3Crect fill='%23d59b57' y='30' width='11' height='11'/%3E%3Crect fill='%23d69956' x='40' width='11' height='11'/%3E%3Crect fill='%23d79755' x='30' y='10' width='11' height='11'/%3E%3Crect fill='%23d89654' x='20' y='20' width='11' height='11'/%3E%3Crect fill='%23da9453' x='10' y='30' width='11' height='11'/%3E%3Crect fill='%23db9252' y='40' width='11' height='11'/%3E%3Crect fill='%23dc9051' x='50' width='11' height='11'/%3E%3Crect fill='%23dd8e50' x='40' y='10' width='11' height='11'/%3E%3Crect fill='%23de8c50' x='30' y='20' width='11' height='11'/%3E%3Crect fill='%23df8a4f' x='20' y='30' width='11' height='11'/%3E%3Crect fill='%23e0884f' x='10' y='40' width='11' height='11'/%3E%3Crect fill='%23e1864e' y='50' width='11' height='11'/%3E%3Crect fill='%23e2844e' x='60' width='11' height='11'/%3E%3Crect fill='%23e3824e' x='50' y='10' width='11' height='11'/%3E%3Crect fill='%23e4804e' x='40' y='20' width='11' height='11'/%3E%3Crect fill='%23e57d4e' x='30' y='30' width='11' height='11'/%3E%3Crect fill='%23e67b4e' x='20' y='40' width='11' height='11'/%3E%3Crect fill='%23e7794e' x='10' y='50' width='11' height='11'/%3E%3Crect fill='%23e8774e' x='70' width='11' height='11'/%3E%3Crect fill='%23e9744f' x='60' y='10' width='11' height='11'/%3E%3Crect fill='%23e9724f' x='50' y='20' width='11' height='11'/%3E%3Crect fill='%23ea6f50' x='40' y='30' width='11' height='11'/%3E%3Crect fill='%23eb6d50' x='30' y='40' width='11' height='11'/%3E%3Crect fill='%23ec6b51' x='20' y='50' width='11' height='11'/%3E%3Crect fill='%23ed6852' x='80' width='11' height='11'/%3E%3Crect fill='%23ed6653' x='70' y='10' width='11' height='11'/%3E%3Crect fill='%23ee6354' x='60' y='20' width='11' height='11'/%3E%3Crect fill='%23ef6055' x='50' y='30' width='11' height='11'/%3E%3Crect fill='%23ef5e56' x='40' y='40' width='11' height='11'/%3E%3Crect fill='%23f05b57' x='30' y='50' width='11' height='11'/%3E%3Crect fill='%23f05858' x='90' width='11' height='11'/%3E%3Crect fill='%23f1555a' x='80' y='10' width='11' height='11'/%3E%3Crect fill='%23f1525b' x='70' y='20' width='11' height='11'/%3E%3Crect fill='%23f2505d' x='60' y='30' width='11' height='11'/%3E%3Crect fill='%23f24d5e' x='50' y='40' width='11' height='11'/%3E%3Crect fill='%23f24a60' x='40' y='50' width='11' height='11'/%3E%3Crect fill='%23f24661' x='90' y='10' width='11' height='11'/%3E%3Crect fill='%23f34363' x='80' y='20' width='11' height='11'/%3E%3Crect fill='%23f34065' x='70' y='30' width='11' height='11'/%3E%3Crect fill='%23f33d67' x='60' y='40' width='11' height='11'/%3E%3Crect fill='%23f33969' x='50' y='50' width='11' height='11'/%3E%3Crect fill='%23f2366b' x='90' y='20' width='11' height='11'/%3E%3Crect fill='%23f2326d' x='80' y='30' width='11' height='11'/%3E%3Crect fill='%23f22e6f' x='70' y='40' width='11' height='11'/%3E%3Crect fill='%23f22a71' x='60' y='50' width='11' height='11'/%3E%3Crect fill='%23f12673' x='90' y='30' width='11' height='11'/%3E%3Crect fill='%23f12175' x='80' y='40' width='11' height='11'/%3E%3Crect fill='%23f01c78' x='70' y='50' width='11' height='11'/%3E%3Crect fill='%23f0177a' x='90' y='40' width='11' height='11'/%3E%3Crect fill='%23ef107d' x='80' y='50' width='11' height='11'/%3E%3Crect fill='%23EE087F' x='90' y='50' width='11' height='11'/%3E%3C/g%3E%3C/svg%3E");
            background-attachment: fixed;
            background-size: cover;
            height: 40%;
            width: 100%;
            position: absolute;
            top: 50%;
            transform: translateY(-70%);
        }
        .main_event{
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            height: fit-content;
            //padding-bottom: 80px;
            img{
                margin-top: 60px;
                width: 100%;
                height: auto;
                object-fit: contain;
                z-index: 1;
            }
            .message{
                height: fit-content;
                width: 70%;
                background: white;
                z-index: 50;
                transform: translateY(-5vh);
                display: flex;
                flex-direction: column;
                align-items: start;
                padding: 30px;
                p{
                    font-size: 1.1rem;
                    line-height: 30px;
                }
                button{
                    position: relative;
                    border: none;
                    font-size: 1.1rem;
                    padding: 10px 40px 10px 40px;
                    float: left;
                    font-weight: bolder;
                    background: #aad4fd;
                    //box-shadow: 0 2px 5px rgba(0,0,0,0.11), 0 5px 5px rgba(0,0,0,0.11);
                }
            }
            /*
              Small devices views will have the skew
             */
            @media only screen and (max-width: 599px) {
                width: 90vw;
            }
            /*
              Tablet and Desktop views will have the skew
             */
            @media only screen and (min-width: 600px) and( max-width: 1080px){
                width: 65vw;
                .message{
                    width: 65%;
                    transform: translate(15vw, -10vh);
                }
            }
            @media only screen and (min-width: 1081px){
                width: 50vw;
                img{
                    transform: translateX(-10vw);
                }
                .message{
                    width: 50%;
                    transform: translate(15vw, -10vh);
                }
            }
        }
    }
</style>
