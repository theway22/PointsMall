<template>
    <div class="header wrap">
        <h1><img src="../assets/img/indexLogo.png" alt=""></h1>
        <div class="nav">
            <ul>
                <li @click="$router.push('/home')" :class="$route.path==='/home'?'active':''">首页</li>
                <li @click="$router.push('/goods')" :class="$route.path==='/goods'?'active':''">全部商品</li>
                <li @click="$router.push('/user')" :class="$route.path==='/user'?'active':''">个人中心</li>
                <li @click="$router.push('/order')" :class="$route.path==='/order'?'active':''">我的订单</li>
                <li @click="$router.push('/free')" :class="$route.path==='/free'?'active':''">专属福利</li>
            </ul>
        </div>
        <div class="search">
            <input type="text">
            <span><img width="15" height="15" src="../assets/img/search.png" alt=""></span>
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
        /* background-color: skyblue; */
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
    .header .nav ul .active{
        color: #0A328E ;
        font-weight: 700;
    }
    .header .search input{
        width: 214px;
        height: 38px;
        border-radius: 20px 0px 0px 20px;
        border: 1px solid #DEDEDE;
        text-indent: 10px;
    }
    .header .search{
        display: flex;
    }
    .header .search span{
        width: 50px;
        height: 40px;
        background: #0A328E;
        border-radius: 0px 20px 20px 0px;
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
    }
    
</style>