<template>
    <svg :class="classes" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
         viewBox="0 0 24 24" stroke="currentColor">
        <path d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
    </svg>
</template>

<script>
    export default {
        props: ['classes']
    }
</script>