<template>
    <div class="style-container">
        <el-row>
            <el-col :span=8>
                <el-image :src="require('@/assets/cake.png')" ></el-image>
            </el-col>
        </el-row>
        <el-row>
            <el-col :span=24>
                <ul>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>   
                </ul>
            </el-col>
        </el-row>
    </div>
</template>

<script>
export default {
    data(){
        return {
            url:'src/assets/cake.png'
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../style/login.scss";
</style>

