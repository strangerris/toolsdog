<script lang='ts' setup>
    const handleClickMini = () => {
        AMessage.info('hello isboyjc, click mini AButton')
    }
</script>

<template>
    <div>hello isboyc, this is toolsdog home page</div>
    <a-space>
        <a-button type="primary" size="mini" @click="handleClickMini">Mini</a-button>
        <a-button type="primary" size="small">Small</a-button>
        <a-button type="primary">Medium</a-button>
        <a-button type="primary" size="large">Large</a-button>
    </a-space>
    <Hello></Hello>
    <icon-ep-alarm-clock class=""/>
    <button class="btn-style">
        Button
    </button>
</template>

<style lang='scss' scoped>
.btn-style{
    @apply bg-blue-400 text-sm text-white font-mono font-light py-2 px-4 rounded border-2 border-blue-200;
    @apply hover:bg-blue-500;
    @apply dark:bg-blue-500 dark:hover:bg-blue-600;
}
</style>