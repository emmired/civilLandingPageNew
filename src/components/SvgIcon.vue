<template>
  <div style="display: flex;" dense class="q-pa-none q-ma-none" v-html="iconsData[name]" />
</template>

<script>
export default {
  name: 'SvgIcon',
  props: {
    name: {
      type: String,
      required: true,
      validator: (value) => {
        // Validate the name prop here if needed
        return [
          'actionArrow',
        ].includes(value);
      },
    },
  },
  data() {
    return {
      iconsData: {
        actionArrow: '<svg xmlns="http://www.w3.org/2000/svg" xml:space="preserve" width="20px" height="20px" version="1.1" fill="#000000" id="Layer_1"  xmlns:xlink="http://www.w3.org/1999/xlink"  viewBox="0 0 792 792" ><path d="M578.035,306.001L272.033,612l-61.022-61.021l244.978-244.978L211.011,61.022L272.033,0L578.035,306.001z M211.735,184.52 L90,306.255l120.701,120.7l121.734-121.734L211.735,184.52z"/></svg>'
      },
    };
  },
};
</script>

<style scoped>
/* Add styling here if needed */
</style>
