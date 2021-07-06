<template>
    <div class="search-module-header">
        <form action="#" class="form__header">
            <input type="text" class="form-input__header">
            <button type="button" class="form-button__header">Search</button>
        </form>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
.search-module-header {
    height: 40px;
    width: 40%;
    background-color: rgb(19, 20, 19);
    display: flex;
    justify-content: center;
    align-items: center;
}
.form__header {
    height: 40px;
    width: 100% ;
    display: flex;
    justify-content: center;
    align-items: center;
}
.form-input__header {
    font-size: 18px;
    outline: none;
    height: 25px;
    width: 60%;
    background-color: rgb(253, 228, 7);
    border: none;
    border-radius: 2px;
}
.form-input__header:hover {
    background-color: rgb(245, 181, 6);
}
.form-button__header {
    margin-left: 10px;
    height: 26px;
    width: 20%;
    background-color: rgb(253, 228, 7);
    border: none;
    border-radius: 2px;
}
.form-button__header:hover {
    background-color: rgb(245, 181, 6);
}
</style>