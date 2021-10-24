<template>
    <div class="testView">
        <p>{{name}} -> {{age}}</p>
        <label style="display: flex; flex-direction: row; width: 100px ; height: fit-content">
            <button @click="changeName('Tuya')">Change name</button>
            <button @click="changeAge(60)">Change age</button>
        </label>
        <p v-for="person in people " :key="person.age">
            {{person.name}}, {{person.age}}, {{person.gender}}
        </p>
    </div>
</template>

<script lang="ts">
import {defineComponent,  reactive, toRefs} from "vue"
import {Person} from "./Person"
export default defineComponent({
    name: "testVue3",
    components: {},
    setup(){
        const state = reactive({
            name: "link",
            age: 25 as string | number,
            people : [
                {name : "link", age : 25, gender : "monke"},
                {name : "Tuya", age : 22, gender : "monke"},
                {name : "Clint", age : 250, gender : "monke"},
                {name : "Obondi", age : 225, gender : "monke"},
                {name: "Kabuto"}
            ] as Person[]
        })
        return {...toRefs(state)}
        /*const name = ref<string>("link")
        const age = ref<string | number>(15)
        const people = ref<Person[]>([
            {name : "link", age : 25, gender : "monke"},
            {name : "Tuya", age : 22, gender : "monke"},
            {name : "Clint", age : 250, gender : "monke"},
            {name : "Obondi", age : 225, gender : "monke"},
            ]
        )
        return {name, age , people}*/
    },
     methods: {
        changeName(name : string){
            this.name = name;
            return name
        },
        changeAge(age : number){
            this.age = age
            return age
        }
     }
})
</script>

<style lang="scss" scoped>

</style>
