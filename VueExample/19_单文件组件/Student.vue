<template>
    <!-- //组件的结构 -->
    <div class="demo">
        <h2>学生姓名：{{ name }}</h2>
        <h2>学生年龄：{{ age }}</h2>
    </div>
</template>

<script>
//组件交互相关的代码（数据、方法等等）
export default {//默认暴露
    name: 'Student',//组件名称
    data() {
        return {
            name: 'DFshmily',
            age: 20

        }
    }
}

</script>

<style>
/*组件的样式*/
.demo {
    background-color: orange;
}
</style>