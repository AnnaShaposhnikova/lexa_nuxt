<template>
    <img :src="src" class="card-img-center img-fluid  px-2 py-2"
         alt="Card image cap">
</template>
<script>
export default {
    props: ["src"],
    name: "CardImg"
}
</script>
