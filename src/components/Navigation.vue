<template>
    <div class="navigation">
        <button type="button" class="button__navigation">CPU</button>
        <button type="button" class="button__navigation">Сooling</button>
        <button type="button" class="button__navigation">Motherboards</button>
        <button type="button" class="button__navigation">RAM</button>
        <button type="button" class="button__navigation">Hard Drives</button>
        <button type="button" class="button__navigation">Power Supply</button>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.navigation {
    margin-right: 10px;
    height: 40px;
    width: 45%;
    background-color: rgb(19, 20, 19);
    display: flex;
    justify-content: center;
    align-items: center;
}
@media screen and (max-width: 800px) {
  .navigation {
    margin-right: 0px;
    height: 40px;
    width: 100%;
    background-color: rgb(19, 20, 19);
    display: flex;
    justify-content: center;
    align-items: center;
    }
}
.button__navigation {
    font-size: 10px;
    margin-left: 6px;
    margin-right: 5px;
    height: 26px;
    width: 15%;
    background-color: rgb(253, 228, 7);
    border: none;
    border-radius: 2px;
    display: flex;
    justify-content: center;
    align-items: center;
}
@media screen and (max-width: 800px) {
.button__navigation {
    font-size: 7px;
    margin-left: 6px;
    margin-right: 5px;
    height: 26px;
    width: 15%;
    background-color: rgb(253, 228, 7);
    border: none;
    border-radius: 2px;
    display: flex;
    justify-content: center;
    align-items: center;
}
}
.button__navigation:hover {
    background-color: rgb(245, 181, 6);
}
</style>