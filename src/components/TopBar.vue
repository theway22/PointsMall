<template>
    <div class="top-bar">
        <div class="wrap top-bar-wrap">
        <div class="l">欢迎来到积分商城</div>
        <div class="r">
            <ul>                     
                <li>
                    <img class="avatar" width="26" src="../assets/img/userImg.f8bbec5e.png" alt="">
                    用户名：游客
                </li>
                <li>我的积分：--</li>
                <li>获取积分</li>
                <li>叩丁狼官网</li>
                <li class="login-btn">登陆</li>
            </ul>
        </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .top-bar{
    width: 100%;
    height: 40px;
    background-color: #242B39;
    
    font-size: 14px;
    color: white;
    text-decoration: none;
    line-height: 40px;
    }
    .top-bar-wrap{
        background-color: skyblue;
        /* height: 40px; */
        display: flex;
        justify-content: space-between;
    }
    .l {
        margin-left: 10px;
    }
    .r ul{
        display: flex;
    }
    .r ul li{
        display: flex;
        align-items: center;
        margin-left: 20px;
        }
    .r ul li .avatar{
        border-radius: 50%;
        margin-right: 6px;
    }
    .login-btn{
        width: 124px;
        height: 40px;
        background: #0A328E;
        justify-content: center;
    }
</style>