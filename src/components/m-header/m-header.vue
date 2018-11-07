<template>
  <div class="m-header">
    <div class="icon"></div>
    <h1 class="text">Music</h1>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../../common/sass/mixin.scss';
@import '../../common/sass/variable';
.m-header {
  position: relative;
  height: 44px;
  text-align: center;
  font-size: 0;
  color: $color-theme;
  .icon {
    display: inline-block;
    vertical-align: top;
    margin-top: 6px;
    width: 30px;
    height: 32px;
    margin-right: 9px;
    @include bg-image('logo');
    background-size: 30px 32px;
  }
  .text {
    display: inline-block;
    vertical-align: top;
    line-height: 44px;
    font-size: $font-size-large;
  }
  .mine {
    position: absolute;
    top: 0;
    right: 0;
    .icon-mine {
      display: block;
      padding: 12px;
      font-size: 20px;
      color: $color-theme;
    }
  }
}
</style>
