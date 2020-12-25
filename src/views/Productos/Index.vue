<template>
    <div class="container">
        <div class="cover">
            <div class="col-md-12">
                <h3>Productos</h3>
            </div>
            <div class="row">
                <div class="col-md-3">
                    <div class="col-md-12">
                        <img src="http://placehold.it/200x100/000"/>
                        <div class="col-md-12">
                            <h4>Titulo del producto 1</h4>
                            <p>Descripcion</p>
                            <router-link :to="{name:'producto', params:{id:1}}" class="btn btn-success btn-sm">Ver detalle</router-link>
                            <!-- <a href="#" class="btn btn-success btn-sm">Agregar al carro</a> -->
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="col-md-12">
                        <img src="http://placehold.it/200x100/000"/>
                        <div class="col-md-12">
                            <h4>Titulo del producto 2</h4>
                            <p>Descripcion</p>
                            <router-link :to="{name:'producto', params:{id:2}}" class="btn btn-success btn-sm">Ver detalle</router-link>
                        </div>
                    </div>
                </div>   
                <div class="col-md-3">
                    <div class="col-md-12">
                        <img src="http://placehold.it/200x100/000"/>
                        <div class="col-md-12">
                            <h4>Titulo del producto 3</h4>
                            <p>Descripcion</p>
                            <router-link :to="{name:'producto', params:{id:3}}" class="btn btn-success btn-sm">Ver detalle</router-link>
                        </div>
                    </div>
                </div>   <div class="col-md-3">
                    <div class="col-md-12">
                        <img src="http://placehold.it/200x100/000"/>
                        <div class="col-md-12">
                            <h4>Titulo del producto 4</h4>
                            <p>Descripcion</p>
                            <router-link :to="{name:'producto', params:{id:4}}" class="btn btn-success btn-sm">Ver detalle</router-link>
                        </div>
                    </div>
                </div>                   
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Productos'
    }
</script>

<style scoped>
    .cover{
        padding: 20px;
        margin: 40px 2px;
        border: 1px solid #dee0e2;
    }
</style>