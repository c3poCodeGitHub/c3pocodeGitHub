<template>
    <div class="login-module">
        <div class="text__login-module">
            <span class="span-text__login-module">Для оступа к корзине и заказам нужно автортзироваться</span>
        </div>
        <div class="button-wrapper__login-module">
            <button class="button__button-wrapper">log In</button>
        </div>
    </div>
</template>

<script>
    export default {
  
    }
</script>

<style  scoped>
.login-module {
    height: 40px;
    width: 99%;
    margin-top: 4px;
    border: 2px solid rgb(19, 20, 19);
    background-color: rgb(253, 228, 7);
    display: flex;
    justify-content: space-around;
    align-items: center;
}
@media screen and (max-width: 800px) {
  .login-module {
    height: 80px;
    width: 95%;
    margin-top: 10px;
    border: 2px solid rgb(19, 20, 19);
    background-color: rgb(253, 228, 7);
    display: flex;
    flex-direction: column;
    /* justify-content: center; */
    align-items: center;

    
}
}
.login-module:hover {
    background-color: rgb(245, 181, 6);
}
.span-text__login-module {
    font-size: 12px;
}
@media screen and (max-width: 800px) {
    .span-text__login-module {
        width: 100%;
        font-size: 9px;
        display: flex;
        justify-content: center;
        align-items: center;
}
}
.button__button-wrapper {
    font-size: 14px;
    margin-left: 6px;
    margin-right: 5px;
    height: 26px;
    width: 200%;
    background-color: rgb(253, 228, 7);
    border: 2px solid rgb(19, 20, 19);
    border-radius: 2px;
    display: flex;
    justify-content: center;
    align-items: center;
}
@media screen and (max-width: 800px) {
  .button__button-wrapper {
    font-size: 12px;
    height: 26px;
    width: 100%;
    background-color: rgb(253, 228, 7);
    border: 2px solid rgb(19, 20, 19);
    border-radius: 2px;
    display: flex;
    justify-content: center;
    align-items: center;
}
}
.button__button-wrapper:hover {
    background-color: rgb(19, 20, 19);
    color: rgb(253, 228, 7);
}
</style>