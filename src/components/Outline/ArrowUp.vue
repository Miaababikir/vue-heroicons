<template>
    <svg :class="classes" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
         viewBox="0 0 24 24" stroke="currentColor">
        <path d="M5 10l7-7m0 0l7 7m-7-7v18"></path>
    </svg>
</template>

<script>
    export default {
        props: ['classes']
    }
</script>