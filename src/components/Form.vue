<template>
    <h2>Meu formulario:</h2>
    <form action="" @submit="enviarFormulario($event)">
        <div><input type="text" v-model="name"></div>
        <div><input type="text" v-model="email"></div>
        <div><Submit /></div>
    </form>
</template>

<script>
    import InputText from './forms/InputText.vue'
    import Submit from './forms/Submit.vue'

    export default {
        name: 'Form',
        components: {
            InputText,
            Submit
        },
        data() {
            return {
                name: 'Lucas',
                email: 'lucas@example.com'
            }
        },
        methods: {
            enviarFormulario(e) {
                e.preventDefault();

                const name = this.name;
                const email = this.email;
                console.log('Formulario enviado!');
                console.log('O nome é: '+name);
                console.log('O email é: '+email);

                // Ajax

                //Inserir no banco de dados
            }
        }
    }
</script>