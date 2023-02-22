<template>
    <div class="ice-header">
        <div class="ice-left">
            <slot name="left"></slot>
        </div>
        <div class="ice-middle">
            <slot name="middle"></slot>
        </div>
        <div class="ice-right">
            <slot name="right"></slot>
        </div>
    </div>
</template>

<script>
export default {
    name: 'IceHeader'
};
</script>

<style lang="scss" scoped>
.ice-header {
    width: 100%;
    box-sizing: border-box;
    padding: 0 16px;
    height: 64px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
</style>
