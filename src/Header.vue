<template>
    <div class="container-flex">
        <div class="header-vacio">
            <div class="container">
                <form class="buscador">
                    <input class="form-control form-control-lg" type="text" placeholder="Buscar...">
                    <i class="fas fa-search"></i>
                </form>
            </div>
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
    .buscador {
        margin-top: 30px;
    }
</style>