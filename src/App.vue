<template>
    <div id="app" class="bg-gray-200 min-h-screen text-gray-800">
        <div class="container mx-auto pt-32">
            <o-adjustments classes="w-8 text-indigo-400 inline-block" />
            <o-annotation classes="w-8 text-indigo-400 inline-block" />
            <s-user classes="w-8 text-indigo-400 inline-block" />
        </div>
    </div>
</template>

<script>
    import { OAdjustments, OAnnotation, SUser } from "./lib";
    export default {
        components: {OAdjustments, OAnnotation, SUser}
    }
</script>

<style lang="scss" src="./assets/app.scss" />
