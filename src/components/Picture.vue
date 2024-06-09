<template>
    <img :src="avatar" :alt="descricao"><!-- ":" é a forma abreviada de v-bind -->
</template>

<script>
export default {
    name: 'Picture',
    data() {
        return {
            avatar: "/img/avatar.png",
            descricao: "Lucas Cabral"
        }
    }
}
</script>