<template>
    <div class="container-flex">
        <div class="header-vacio">
            <div>Holamanola.</div>
        </div>
        </div>
</template>

<script>
    module.exports = {
        name: 'header',
        data: function() {
            return {
                buscador: ''
            }
        }
    }
</script>

<style scoped>
    .header-vacio {
        background: #003399;
        height: 30vh;
        color: bisque;
    }
</style>