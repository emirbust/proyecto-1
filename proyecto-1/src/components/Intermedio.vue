<template>
    <div class="container" id="container"> 
        
            <div class="columns">

                <div class="column is-3">
                    <a href="https://bulma.io/" target="_blank">
                        <div class="card">
                            <div class="card-image">
                                <figure class="image is-16by9">
                                    <img class="is-rounded" src="@/assets/bulma.png"  alt="">
                                </figure>
                            </div>
                            <div class="card-content ">
                                <div class="content ">
                                    <h1 class="is-size-4">
                                        bulmeaq
                                    </h1>
                                    <p>la pagina para todo el estilo de la pagina web</p>
                                </div>
                            </div>
                        </div>
                    </a>
                </div>

                <div class="column is-3">
                    <a href="https://buefy.org/" target="_blank">
                        <div class="card">
                            <div class="card-image">
                                <figure class="image is-16by9">
                                    <img src="@/assets/buefy.jpg" alt="">
                                </figure>
                            </div>
                            <div class="card-content ">
                                <div class="content ">
                                    <h1 class="is-size-4">
                                        buefy
                                    </h1>
                                    <p>utiliza su propio sistema y el de bulma y si no anda bulma esto si</p>
                                </div>
                            </div>
                        </div>
                    </a>
                </div>

                <div class="column is-3">
                    <a href="https://www.youtube.com/watch?v=cqMfPS8jPys&list=PLhSj3UTs2_yVHt2DgHky_MzzRC58UHE4z" target="_blank">
                        <div class="card">
                            <div class="card-image">
                                <figure class="image is-16by9">
                                    <img src="@/assets/14570827460633_illu-cours_html5-css3.png" alt="">
                                </figure>
                            </div>
                            <div class="card-content ">
                                <div class="content ">
                                    <h1 class="is-size-4">
                                        HTML
                                    </h1>
                                    <p>es la estructura basica de todo prpgrama</p>
                                </div>
                            </div>
                        </div>
                    </a>
                </div>

                <div class="column is-3">
                    <a href="https://vuejs.org/" target="_blank">
                        <div class="card">
                            <div class="card-image">
                                <figure class="image is-16by9">
                                    <img src="@/assets/vue.jpg"  alt="">
                                </figure>
                            </div>
                            <div class="card-content ">
                                <div class="content ">
                                    <h1 class="is-size-4">
                                        VUE
                                    </h1>
                                    <p>es el framework que convina javascrip con HTML y CSS </p>
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            </div>

            <div class="columns">
                <div class="column is-3 is-one-third">
                    <a href="https://cli.vuejs.org/" target="_blank">
                        <div class="card">
                            <div class="card-image">
                                <figure class="image is-16by9">
                                    <img src="@/assets/vue-cli-3.png">
                                </figure>
                            </div>
                            <div class="card-content ">
                                <div class="content ">
                                    <h1 class="is-size-4">
                                        VUE CLI
                                    </h1>
                                    <p>es el enterno de interfaz grafica de la pagina</p>
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            </div>

    </div>

</template>

<script>
export default {
    name:'Intermedio'
}
</script>>

<style scoped>
.container .card:hover{
    transform: translate(-15px) scale(1.15);
    box-shadow: 0 12px 16px rgba(0, 0, 0, 0.233);
    background: rgb(5, 88, 75);
    color:rgb(255, 255, 255);
    transition: 0.15s;
}
.container .card:hover h1{
color:rgb(253, 255, 255);
}

.container{
    opacity: 0;
    transition: 1s linear 1s;
}
.container.imagenes-cargadas{
    opacity: 1;
}
.card{
    border-radius: 10px;
}
.card-image{
    border-radius: 10px;
}
.img{
    border-radius: 10px;
}
.image{
    border-radius: 10px;
}
</style>
