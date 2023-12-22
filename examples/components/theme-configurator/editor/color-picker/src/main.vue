<template>
  <div></div
></template>

<script>
// import Color from "./color";
// import PickerDropdown from "./components/picker-dropdown.vue";
// import Clickoutside from 'element-ui/src/utils/clickoutside';
// import Emitter from 'element-ui/src/mixins/emitter';

export default {
  name: "ElColorPicker",

  props: {
    value: String,
    showAlpha: Boolean,
    colorFormat: String,
    disabled: Boolean,
    size: String,
    popperClass: String,
    predefine: Array,
    colorList: Array,
  },

  inject: {
    elForm: {
      default: "",
    },
    elFormItem: {
      default: "",
    },
  },

  computed: {
    // displayedColor() {
    //   if (!this.value && !this.showPanelColor) {
    //     return "transparent";
    //   }

    //   return this.displayedRgb(this.color, this.showAlpha);
    // },

    // _elFormItemSize() {
    //   return (this.elFormItem || {}).elFormItemSize;
    // },

    // colorSize() {
    //   return this.size || this._elFormItemSize || (this.$ELEMENT || {}).size;
    // },

    // colorDisabled() {
    //   return this.disabled || (this.elForm || {}).disabled;
    // },
  },

  watch: {
    // value(val) {
    //   if (!val) {
    //     this.showPanelColor = false;
    //   } else if (val && val !== this.color.value) {
    //     this.color.fromString(val);
    //   }
    // },
    // color: {
    //   deep: true,
    //   handler() {
    //     this.showPanelColor = true;
    //   },
    // },
    // displayedColor(val) {
    //   if (!this.showPicker) return;
    //   const currentValueColor = new Color({
    //     enableAlpha: this.showAlpha,
    //     format: this.colorFormat,
    //   });
    //   currentValueColor.fromString(this.value);

    //   const currentValueColorRgb = this.displayedRgb(
    //     currentValueColor,
    //     this.showAlpha
    //   );
    //   if (val !== currentValueColorRgb) {
    //     this.$emit("active-change", val);
    //   }
    // },
  },

  methods: {
   
  },

  mounted() {
    // const value = this.value;
    // if (value) {
    //   this.color.fromString(value);
    // }
    // this.popperElm = this.$refs.dropdown.$el;
  },

  data() {
    // const color = new Color({
    //   enableAlpha: this.showAlpha,
    //   format: this.colorFormat,
    // });

    // return {
    //   color,
    //   showPicker: false,
    //   showPanelColor: false,
    // };
  },

  components: {
  },
};
</script>
