<template>
    <div class="notification">
        {{ body }}
    </div>
</template>

<script>
    export default {
        data() {
            return {
                body: 'I am a notifications.'
            }
        }
    }
</script>

<style>
    .notification {
        background: grey;
    }
</style>