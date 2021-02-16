<template>
    <div class="default">
        <title>sfdds</title>
        <navbar :user="user"></navbar>
        <router-view></router-view>
    </div>
</template>

<script>
    import Navbar from "../components/navbar";
    export default {
        name: "Default",
        components: {Navbar},
        data(){
            return {
                user:{}
            }
        }
    }
</script>

<style scoped>

</style>