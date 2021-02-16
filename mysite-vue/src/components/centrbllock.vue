<template>
    <div>
        <div class="bg-dark  text-center text-white overflow-hidden">
            <div class="my-3 py-3">
        <h2 class="display-5">{{centrbllock.title}}</h2>
        <p class="lead">{{centrbllock.body}}</p>
            </div>
            <div class="bg-light shadow-sm mx-auto" style="width: 80%; height: 300px; border-radius: 21px 21px 0 0;">
                <img class="image" :src= "centrbllock.image" alt=""/>
           </div>
        </div>


    </div>
</template>

<script>
    export default {
        name: "centrbllock",
        props:{
            centrbllock:{
                type: Object,
                required: true
            }
        }
    }
</script>

<style scoped>
.image{
    width: 100%;
    height: 300px;
    border-radius: 21px 21px 0 0;
}
</style>