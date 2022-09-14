<template>
  <div class="modal">
    <div class="form-asses">sss</div>
    <button @click="close">theem</button>
  </div>
</template>
<script>
export default {
  name: "MsPopupAsset",
  props: {
    statePopup: {
      default: false,
    },
  },
  methods: {
    close(){
      this.$parent.close();
    }
  },
  setup(props) {
    // function show() {
    //   props.statePopup = true;
    // }

    return {
      // show,
    };
  },
};
</script>
<style lang="scss" scoped>
@import "./../../assets/scss/components/MsPopupAsset.scss";
</style>
