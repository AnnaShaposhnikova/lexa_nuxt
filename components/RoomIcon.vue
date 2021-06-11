<template>
    <div class="media-icon">
        <img :src="src" class="icon">
        <span>{{description}}</span>
    </div>

</template>
<script>
export default {
    props: {src: String,
        description: String,

    },

    name: "RoomIcon"
}
</script>
