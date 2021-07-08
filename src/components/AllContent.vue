<template>
    <div class="all-content">
        <ItemsBox />
    </div>
</template>

<script>
import ItemsBox from './ItemsBox.vue';

    export default {
        components: {
            ItemsBox,
        }
    }
</script>

<style scoped>
.all-content {
    height: calc(100vh - 50px);
    width: 100%;
    background-color: rgb(253, 228, 7);
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>