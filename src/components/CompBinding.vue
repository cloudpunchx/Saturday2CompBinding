<template>
    <div>
        <!-- the mustache syntax, in here you can actually write any valid JS (just don't make it too big/complicated)-->
        {{counter}}
        <!-- ternary operators can be put here, where value depends on a condition -->
        {{counter > 5 ? "large" : "small"}}
        <button>Button Increment</button>
    </div>
</template>

<script>
    export default {
        name : "CompBinding",
        data() {
            return {
                counter: 0
            }
        },
        methods: {
            increment() {
                this.counter++
            }
        },
        mounted () {
            document.querySelector(`button`).addEventListener(`click`, this.increment);
        },
    }
</script>

<style scoped>

</style>