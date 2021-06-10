<template>
    <b-navbar toggleable="lg" type="light" >
       <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="mx-auto">
                <b-nav-item to="/">Главная</b-nav-item>
                <b-nav-item to="/rooms">Номера</b-nav-item>
                <b-nav-item to="/price">Цены</b-nav-item>
                <b-nav-item to="/restzone">Контакты</b-nav-item>
                <b-nav-item to="/restzone">Территория гостевого дома</b-nav-item>
                <b-nav-item to="/fotogellary">Фотогаллерея</b-nav-item>
                <b-nav-item to="/services">Услуги</b-nav-item>
                <b-nav-item to="/beach">Пляжи</b-nav-item>
                <b-nav-item to="/settlement">О посёлке</b-nav-item>
            </b-navbar-nav>
        </b-collapse>
    </b-navbar>


</template>

<script>
export default {
    name: "Nav"
}
</script>

<style scoped>

</style>

