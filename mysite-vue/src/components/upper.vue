<template>
    <div class="up">
        <div class="hidden">
            <h1>Великий заголовок</h1>
            <p>Мало половин, мало мало половин</p>
        </div>
        <div class="hidden2">
                <div class="row">
                    <div class="col-lg-4">
                        <img src="../assets/lesha.jpg" class="bd-placeholder-img rounded-circle" width="140" height="140" aria-label="Placeholder: 140x140" alt="">
                        <h2>Самые пизатые</h2>
                        <p> Самые пиздатые парни готовы на все, чтобы красотулечные саты заполнили весь интернет</p>
                        <p><a class="btn btn-secondary" href="#" role="button">Подробнее »</a></p>
                    </div><!-- /.col-lg-4 -->
                    <div class="col-lg-4">
                        <img src="../assets/java.jpg" class="bd-placeholder-img rounded-circle" width="140" height="140" aria-label="Placeholder: 140x140" alt="">
                        <h2>Невероятные</h2>
                        <p>Невероятные работы наглядно демонстрируют всю силу и мощь этих парней. Без рофлов- они заебулички.</p>
                        <p><a class="btn btn-secondary" href="#" role="button">Подробнее »</a></p>
                    </div><!-- /.col-lg-4 -->
                    <div class="col-lg-4">
                        <img src="../assets/denis.jpg" class="bd-placeholder-img rounded-circle" width="140" height="140" aria-label="Placeholder: 140x140" alt="">
                        <h2>Джавовые</h2>
                        <p>Джавовые разработки сотворят невероятное. Сайты оживают на глазах, и не умирают никогда. Внатуре говорю, живуче не бывает.</p>
                        <p><a class="btn btn-secondary" href="#" role="button">Подробнее »</a></p>
                    </div><!-- /.col-lg-4 -->
                </div><!-- /.row -->

        </div>
    </div>
</template>

<script>
    export default {
        name: "upper"
    }
</script>

<style scoped>
.up{
    background: linear-gradient(to right, #b92b27, #1565c0);
    background-attachment: fixed;
    text-align: center;
    height: 100%;
   vertical-align: center;

}
.hidden{
    opacity: 0%;
    animation: showDiv 2s forwards;
    margin-top: 5%;
    margin-bottom: 5%;
}
.hidden2{
    opacity: 0%;
    animation: showDiv 8s forwards;
    margin-bottom: 10%;
}
@keyframes showDiv {
    0%,
    99% {

    }
    100% {

        opacity: 100%;
    }
}
</style>