<script setup>
    const props = defineProps({
        msg: String,
    })

    const a = "Sou um texto da variável A"
    console.log(a)
</script>

<template>
    <div>
        <!-- coloquei o TD s@o pra visualizar melhor o que está acontecendo -->
        Sou um componente dentro do DIV
        <td>{{ a }}</td>
        <td>{{ props.msg }}</td>
    </div>
    Sou um texto do HTML fora do DIV
</template>
