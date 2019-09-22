<template>
    <button @click="addTest">Test</button>
</template>

<script>
export default {
methods: {
    addTest(){
        this.$emit('test-alert')
    }
}
}
</script>

