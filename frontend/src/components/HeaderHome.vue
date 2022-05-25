<template>
    <header class="header-home">
        <img src="../assets/Logo-groupomania.png" alt="Logo Groupomania">
    </header>
  
</template>

<script>
export default {
    name: 'HeaderHome'
}
</script>

<style scoped lang="scss">
header {
    display: flex;
    align-items: center;
    height: 60px;
    background: linear-gradient(rgb(0, 119, 255) 25%, rgb(130, 188, 238));
    padding: 10px;
    
    img {
       width: 150px;
       height: 27px;
       object-fit: cover;
    }
}
</style>