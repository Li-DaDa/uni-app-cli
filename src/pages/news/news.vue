<template>
  <view class="content">
    <view>
      <text class="title">{{ title + stateCount }}</text>
    </view>
  </view>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import { State, Action, Mutation } from "vuex-class";

@Component({})
export default class News extends Vue {
  title = "abc";
  @State("msg") stateCount: any;
}
</script>

<style lang="scss">
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  .title {
    font-size: 36rpx;
    color: #f00;
  }
}
</style>
