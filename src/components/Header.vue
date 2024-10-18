<template>
    <div class="header wrap">
        <h1><img src="../assets/img/indexLogo.png" alt=""></h1>
        <div class="nav">
            <ul>
                <li>首页</li>
                <li>全部商品</li>
                <li>个人中心</li>
                <li>我的订单</li>
                <li>专属福利</li>
            </ul>
        </div>
        <div class="search">
            <input type="text">
            <span><img src="../assets/img/search.png" alt=""></span>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .header{
        height: 118px;
        background-color: skyblue;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .header .nav ul{
        display: flex;
        width:500px;
        justify-content: space-around;
    }
    .header ul li{
        cursor: pointer;
        font-family: SourceHanSansSC;
        font-weight: 500;
        font-size: 16px;
    }
    .header ul li:first-child{
        color: #0A328E;
        font-weight: 800;
    }
    
</style>