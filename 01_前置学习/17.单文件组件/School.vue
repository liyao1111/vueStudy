<template>
<!-- 组件结构 -->
<div id="root">
    <h3>{{name}}</h3>
    <h4>{{age}}</h4>
</div>
</template>
<script>
// 组件交互相关代码
export default {
    name:'school',
    data() {
        return {
            name:'tom',
            age:18
        }
    }
}
</script>
<style>
/* 组件样式 */
.root{
    width: 500px;
    height: 200%;
    background-color: #bfa;
}
</style>