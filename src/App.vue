<template>
    <div id="app">
        <ice-header>
            <template v-slot:left>
                <img src="./assets/header_dark.svg" alt="icon">
            </template>
            <template v-slot:middle>
                <div class="middle-button-group">
                    <div class="navigator-group">
                    </div>
                    <div class="search-group"></div>
                </div>
            </template>
            <template v-slot:right>
                <div class="profile"></div>
            </template>
        </ice-header>
    </div>
</template>

<style lang="scss">
body {
    margin: 0;
    background: #05020e;
}

#app {
    height: 100vh;
}
.profile {
    height: 26px;
    width: 26px;
    border-radius: 50%;
    background: white;
}
.middle-button-group {
    height: 48px;
    width: 248px;
    background: #fff;
}
</style>
<script>
import IceHeader from '@/components/IceHeader/index.vue';

export default {
    components: {IceHeader}
};

</script>
