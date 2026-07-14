<script setup>
    import loginComponent from '../components/loginComponent.vue';
    import navBar from '../components/navBar.vue';
</script>

<template>
    <!-- <navBar/> -->
    <div class="login">
        <loginComponent/>
    </div>
</template>

<style scoped>
.login{
    height: 100vh;
    width: auto;
    
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>