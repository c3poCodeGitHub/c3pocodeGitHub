<template>
    <div class="items-box__all-content">
        <LoginModule  />
    </div>
</template>

<script>
import LoginModule from './LogInModule';

    export default {

        components: {
            LoginModule
        }
    }
</script>

<style  scoped>
.items-box__all-content {
    height: 97.7%;
    width: 97.7%;
    border: 5px solid rgb(19, 20, 19);
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>