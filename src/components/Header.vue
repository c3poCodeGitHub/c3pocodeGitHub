<template>
  <div class="header">
    <div class="logo__header">
      <span class="logo-text__header">Technical Process</span>
    </div>
    <SearchModule />
    <Navigation />
  </div>
</template>

<script>
import SearchModule from './SearchModule.vue';
import Navigation from './Navigation.vue';

export default {
  name: 'Header',
  components: {
    SearchModule,
    Navigation,
  }
}
</script>

<style scoped>
.header {
  height: 50px;
  width: 100%;
  background-color: rgb(253, 228, 7);
  display: flex;
  justify-content: space-around;
  align-items: center;
}
@media screen and (max-width: 800px) {
  .header {
    height: 130px;
    width: 100%;
    background-color: rgb(253, 228, 7);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
}
.logo__header {
  margin-left: 10px;
  height: 40px;
  width: 15%;
  background-color: rgb(19, 20, 19);
  display: flex;
  justify-content: center;
  align-items:center;
}
@media screen and (max-width: 800px) {
  .logo__header {
    margin-left: 0px;
    height: 40px;
    width: 100%;
    background-color: rgb(19, 20, 19);
    display: flex;
    justify-content: center;
    align-items:center;
  }
}
.logo-text__header {
  margin-left: 10px;
  color: rgb(253, 228, 7);
  font-size: 16px;
}
.logo-text__header:hover {
    color: rgb(245, 181, 6);
}
</style>

// Нужно подогнать основной Желтый!!!

@media screen and (max-width: 800px) {
  
}