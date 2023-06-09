<template>
    <div v-bind:id="dynamicId" v-bind:class="msg"> 测试属性绑定</div>
</template>
<script>

export default{
    data() {
        return {
            msg:'active',
            dynamicId:'appId'
        }
    },
}
</script>
