<template>
    <header>
        <button>Resumo</button>
        <button @click="MostrarContato">Contato</button>
    </header>
    <div>
        <Contact></Contact>
        <Resume></Resume>
    </div>
</template>

<script>
import Contact from './Render/Contact.vue'
import Resume from './Render/Resume.vue'

export default{
    name: 'Site',
    components: {
        Contact,
        Resume
    },
    methods:{
        MostrarContato(){
            console.log("Mostrar Contato");
        }
    }
}

</script>

<style>

</style>