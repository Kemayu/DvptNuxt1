<script setup lang="ts">
const route = useRoute()
// Lorsque vous accédez à /posts/1, route.params.id vaudra 1
console.log(route.params.id)
</script>
<template>
    <div>
        <h1 v-if="route.params.id==='1'">C'est l'heure du duel</h1>
        <h1 v-if="route.params.id==='2'">Pikachu</h1>
    </div>
</template>