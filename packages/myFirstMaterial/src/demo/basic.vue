<template>
  <tooltip-button tip="button tip">Demo Basic</tooltip-button>
</template>

<script lang="ts">
import TooltipButton from 'lh-ic-table';

// 目前vue-live导出defineComponent存在问题，所以仅支持普通对象导出。
export default {
  name: 'BasicDemo',
  components: {
    TooltipButton,
  },
};
</script>
