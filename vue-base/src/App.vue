
<template>
  <my-options-api-style></my-options-api-style>
  <my-composition-api-style></my-composition-api-style>
  <show-count-result></show-count-result>
  <compute-attribute></compute-attribute>
  <my-component></my-component>
  <my-attribute></my-attribute>
</template>

 


<script>


// 引入组件
import MyComponent from './components/MyComponent.vue'
import MyAttribute from './components/MyAttribute.vue'
import ComputeAttribute from './components/ComputeAttribute.vue'
import ShowCountResult from './components/ShowCountResult.vue'
import MyCompositionApiStyle from './components/MyCompositionApiStyle.vue'
import MyOptionsApiStyle from './components/MyOptionsApiStyle.vue'

export default {

  // 第二步注入组件
  components: { MyComponent, MyAttribute, ComputeAttribute, ShowCountResult, MyCompositionApiStyle, MyOptionsApiStyle, }


}

</script>

