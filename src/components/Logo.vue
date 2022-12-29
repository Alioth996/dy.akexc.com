<template>
    <div class="logo">
        <div class="logo-bg">
        </div>
        <h1>
            <a href="#">侗 语</a>
        </h1>
    </div>
</template>
<style scoped lang="less">
.logo {
    position: relative;
    height: 6em;
    padding: 1.5em;
    cursor: pointer;

    .logo-bg {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(-45deg, #47caff 50%, #646cff 50%);
        filter: blur(66px);
        opacity: 0;
        transition: .2s;

        &:hover {
            opacity: 1;
        }
    }

}
</style>
  