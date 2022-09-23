<template>
    <main>
        <div class="container">
            --- CONTENT GOES HERE ---
        </div>
    </main>
</template>

<script>
export default {
    name: 'MainComponent',
};
</script>

<style scoped lang="scss">
@import '@/styles/variables.scss';

main {
    background-color: $bg-main;
    color: $color-main;
    padding: 50px 0px;
}
</style>