<template>
<div class="app">
    <vue-editor></vue-editor>
</div>
</template>

<script>
import VueEditor from './VueEditor.vue';
export default {
    data() {
        return {
            name: 'App'
        }
    },
    components: {
        VueEditor
    }
}
</script>

<style lang="css">
</style>
