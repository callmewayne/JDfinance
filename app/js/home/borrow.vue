<template lang="html">
  <Panel title='极速借贷' :class='$style.panel'>
       <section :class='$style.content'>
             <router-link :to="{name:'home'}">
                 <img src='//img12.360buyimg.com/jrpmobile/jfs/t14707/121/2335216734/37656/5611f3d9/5a97704dNca58d124.png?width=750&height=270'>
             </router-link>
       </section>
  </Panel>
</template>
<script>
import Panel from "../core/panel.vue";
export default {
  components: {
    Panel
  }
};
</script>
<style lang="scss" module>
@import "../../css/element.scss";
.panel {
  @include panel;
  .content {
    padding-bottom: 40px;
    img {
      display: block;
      width: 100%;
    }
  }
}
</style>

