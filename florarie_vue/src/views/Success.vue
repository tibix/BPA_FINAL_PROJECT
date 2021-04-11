<template>
    <div class="page-success">
        <div class="columns is-multiline">
            <div class="column is-12">
                <h1 class="title">Multumim!</h1>

                <p>Comanda ta va fi procesata in urmatoarele 48 de ore!</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Success',
    mounted() {
        document.title = 'Succes | eFlorarie'
    },
}
</script>