<template>
    <div class="song">
        <Songs/>
    </div>
</template>

<script>
// @ is an alias to /src
import Songs from '@/components/Songs.vue'

export default {
    name: 'Song',
    components: {
        Songs
    }
}

</script>