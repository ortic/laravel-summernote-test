<template>
    <div></div>
</template>

<script>
    export default {
        mounted() {            
            require('summernote')
            $(this.$el).summernote()
        }
    }
</script>
