<template>
    <div class="member">
        <Members/>
    </div>
</template>

<script>
// @ is an alias to /src
import Members from '@/components/Members.vue'

export default {
    name: 'Member',
    components: {
        Members
    }
}
</script>