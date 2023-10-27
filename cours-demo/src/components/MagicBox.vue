<script>
    export default {
        data() {
            return {
                hidden: true
            }
        }
    }
</script>

<template>
  <div class="bloc" v-show="hidden" @click="false">
    Magic Box
  </div>
</template>

<style>
    .bloc {
        background-color: black;
        width: 200px;
        height: 200px;
}
</style>