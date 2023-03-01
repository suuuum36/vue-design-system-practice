<template>
    <button :class="[name, type, size, state, ic_start, ic_end]">버튼명</button>
</template>

<script>
export default {
    props: {
        name: {type: String, default: 'primaryButton'},
        type: {type: String, default: 'solid'},
        size: {type: String, default: 'large'},
        state: {type: String, default: 'normal'},
        ic_start: {type: Boolean, default: false},
        ic_end: {type: Boolean, default: true},
    },
};
</script>

<style scoped>
    button {
        border-radius: 8px;
    }
</style>