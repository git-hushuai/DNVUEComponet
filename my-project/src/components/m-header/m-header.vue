

<template>
    <div class="m-header">
        <h1 class="text">VMusic</h1>
        <router-link to="/user" class="mine" tag="div">
            <i class="iconfont icon-list"></i>
        </router-link>

        <router-link to="/search" class="search" tag="div">
            <i class="iconfont icon-search"></i>
        </router-link>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import "@/common/scss/variable.scss";
@import "@/common/scss/ali-icon.scss";
.m-header {
    position: absolute;
    height: 64px;
    width: 100%;
    text-align: center;
    background: $color-theme;
    top: 0;
    left: 0;
    .text{
        line-height: 44px;
        font-weight: bold;
        color: $color-text-l;
        letter-spacing: 3px;
    }

    .mine{
        position: absolute;
        top: -1.5px;
        left: 0;
        .iconfont{
            display: block;
            padding: 11px;
            font-size: 18px;
            color: $color-theme-l;
        }
    }
    .search {
    position: absolute;
    top: 0;
    right: 2px;
    .iconfont {
        display: block;
        padding: 12px;
        font-size: 18px;
        color: $color-theme-l;
    }
  }
}
</style>



