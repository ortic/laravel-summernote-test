<template>
    <div></div>
</template>

<script>
    export default {
        mounted() {
            var jquery = require('jquery')
            require('summernote')
            jquery(this.$el).summernote()
        }
    }
</script>
