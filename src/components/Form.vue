<template>
    <h2>Meu formulario:</h2>
    <form action="">
        <div><InputText /></div>
        <div><InputText /></div>
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
        }
    }
</script>