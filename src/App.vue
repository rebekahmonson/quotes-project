<template>
    <div class="container">
        <app-quote-grid :quotes="quotes"></app-quote-grid>
    </div>
</template>

<script>
    import QuoteGrid from './components/QuoteGrid.vue'

    export default {
        data() {
            return {
                maxQuotes: 10,
                quotes: [
                    'Here is a starter quote.'
                ],
            }
        },
        components: {
            'app-quote-grid': QuoteGrid
        }
    }
</script>

<style>
</style>
