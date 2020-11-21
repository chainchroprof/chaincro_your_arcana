<template>
  <div>
    <label>
      <input type="checkbox" name="CheckEntry" v-model="checked">
      <img :src="src">
    </label>
     {{ src }}
  </div>
</template>

<script>
/* eslint-disable no-console */
export default {
  name: 'CheckEntry',
  props: {
    checked: { type: Boolean, default: false },
    src: { type: String, default: '' },
  },
}
</script>
