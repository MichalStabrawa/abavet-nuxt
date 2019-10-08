<template>
<div class="container">
    <div class="error">
        <h1>{{error}}</h1>
    </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            error: "Ups... coś poszło nie tak"
        }
    }
}
</script>

<style lang="scss" scoped>
.error {
    width: 100%;
    height: calc(100vh - 300px);
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>


    
