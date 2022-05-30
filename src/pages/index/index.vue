<template>
	<view class="content">
    <input />
    <view style="flex: 1"></view>
    <view class="footer">
      <view class="option">提交</view>
    </view>
	</view>
</template>

<script lang="ts" src="./index.ts"></script>

<style lang="scss">
	.content {
    width: 100vw;
    height: 100vh;
		display: flex;
		flex-direction: column;
		/*align-items: center;*/
		/*justify-content: center;*/

    .footer {
      width: 100vw;
      height: 160rpx;
      text-align: center;
      display: flex;
      align-items: center;
      justify-content: center;

      .option {
        width: 480rpx;
        height: 80rpx;
        border-radius: 40rpx;
        color: white;
        background-color: #0079FE;
        display: flex;
        align-items: center;
        justify-content: center;
      }
    }
	}
</style>
