<template>
    <div>
        <figure class="serv">
            <img :src="src">
        </figure>
        <div class="text-center">
            <p>{{text}}</p>
        </div>
    </div>

</template>
<script>
export default {
    props: {
        src: String,
        text: String,
    },
    name: "Services"
}
</script>
