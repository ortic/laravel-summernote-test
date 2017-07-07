<template>
    <div></div>
</template>

<script>
    require('summernote/dist/summernote.css')

    export default {
        mounted() {
            var jQuery = require('jquery')
            require('bootstrap/js/tooltip')
            require('summernote')
            jQuery(this.$el).summernote()
        }
    }
</script>
