<template>
    <div class="row2">
        <Centrbllock class="item" v-for="(centrbllock, index) in centrbllocks" :key="index" :centrbllock ="centrbllock"/>
    </div>
</template>

<script>
    import Centrbllock from "./centrbllock";
    export default {
        name: "centrbllocks",
        components: {Centrbllock},
        data() {
            return{
                centrbllocks: [
                    {
                        title: 'Джавка',
                        body: 'Лучшее, что придумали люди, подадим вам на блюди',
                        image: require('../assets/java.jpg')
                    },
                    {
                        title: 'сиэсэска',
                        body: 'Как девушка, только краше',
                        image: require('../assets/css.jpg')
                    },
                    {
                        title: 'аштимл',
                        body: 'Без него никуда. Ну а хули, тэги, боди, все дела',
                        image: require('../assets/html.jpg')
                    },
                    {
                        title: 'Мошна',
                        body: 'Место для какой-то машны, но хуй его какой шушун написать',
                        image: require('../assets/moshna.jpg')
                    }
                ]
            }
        }
    }
   </script>

<style scoped>
    .row2{
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        flex-wrap: wrap;
        overflow-x: hidden;
    }
    .item{
        width: 50%;
        height: 70%;
    }
</style>