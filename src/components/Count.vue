<template>
    <div id="count-app">
        <div class="count-number">{{count}}</div>
        <input type="button" value="+" @click="clickCountUp">
        <input type="button" value="-" @click="clickCountDown">
        <p v-if="count === 0">click count up!!</p>
    </div>
</template>

<script>
    export default {
        name: 'CountApp',
        data() {
            return {
                count: 0
            }
        },
        methods: {
            clickCountUp: function() {
                this.count++
            },
            clickCountDown: function() {
                if (this.count > 0) {
                    this.count--
                }
            }
        }
    }

</script>