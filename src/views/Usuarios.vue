<template>
    <div class="container">
        <h1>Informacion de usuario</h1>
        <router-link :to="{ name:'Usuarios', params:{id: item} }" 
            v-for="(item, key) in ArregloUsuarios" :key="key">
            <button>{{ item }}</button>
        </router-link>
        <Usuario />
    </div>
</template>

<script>
import Usuario from '../components/Usuario.vue'
    export default {
        data(){
            return{
                ArregloUsuarios:['Grover','Luisa','Alberto','Carla']
            }
        },
        components:{
            Usuario
        }
    }
</script>

<style scoped>

</style>