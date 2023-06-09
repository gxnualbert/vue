
<template>

<compute-attribute></compute-attribute>
<MyComponent/>
<my-attribute></my-attribute>

</template>

 


<script>


// 引入组件
import MyComponent from './components/MyComponent.vue' 
import MyAttribute from './components/MyAttribute.vue'
import ComputeAttribute from './components/ComputeAttribute.vue'

export default {

  // 第二步注入组件
  components: { MyComponent, MyAttribute, ComputeAttribute }
  

}

</script>

