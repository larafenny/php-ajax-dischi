<template>
    <div class="container">
        <div class="logo">
            <img src="@/logo.png" alt="logo">
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeaderComponent'

}
</script>

<style lang="scss" scoped>
    .container{
        height: 80px;
        display: flex;
        background-color: #2e3a46;
        
    }
    .logo{
        width: 80px;
        padding: 5px;

        img{
            height: 100%;

        }
    }

</style>