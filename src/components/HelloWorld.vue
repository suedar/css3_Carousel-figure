
<script>
export default {
  name: 'vue-css-cf',
  data() {
    return {
    }
  },
  props: {
      width: {
          type: Number,
          default: 300
      }
  },
  render(h) {
    const { width } = this.$props;
    const imgs = this.$slots.default.map(img => h('li', [h(img)]));
    // console.log(imgs)
    return h('div', {
      'class': 'vue-css-cf',
    }, [
      h('ul', )
    ])
  }
}
</script>

<style scoped lang="scss">

</style>
