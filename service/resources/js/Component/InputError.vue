<template>
    <div v-show="message">
        <p class="text-sm text-red-600">
            {{ __(message) }}
        </p>
    </div>
</template>

<script>
    export default {
        props: ['message']
    }
</script>
