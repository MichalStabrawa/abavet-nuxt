<template>
    <section class="fix-background">
<p class="doctors-content">"Bycie lekarzem weterynarii wymaga bardzo dużo poświęcenia, ten zawód trzeba kochać tak samo, jak kocha się zwierzęta. Tacy właśnie jesteśmy, wciąż pogłębiamy swoją wiedzę, a empatia do zwierząt i ich właścicieli pomaga nam w codziennej pracy. Dlatego zawsze chętnie pomożemy, doradzimy i wyleczymy Waszego pupila."</p>
    </section>
    
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.fix-background {
    background-image:linear-gradient(to bottom, rgba(250, 250, 250, 0.52), rgba(250, 250, 250, 0.73)),url('../assets/img/twowet.jpeg');
    height: 350px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding-left: 50px;
    padding-right: 50px;

    .doctors-content {
        width: 50%;
        height: 100%;
        display: flex;
        align-items: center;
font-size: 22px;
    }
    

}
</style>


