<template>
    <header>
        <h1 class="display-2">{{ title }}</h1>
        <p class="lead">Turn your thoughts into power</p>
    </header>
</template>

<script>
export default {
    name: 'Title',
    props: {
        title: String
    }
}
</script>

<style scoped>

h1 {
    text-transform: uppercase;
    letter-spacing: 1rem;
}

</style>