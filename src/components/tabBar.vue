<template>
    <div class="tabBar">
        <router-link to='/' tag="li"><i class="el-icon-house"></i><span>首页</span></router-link>
        <router-link to='/shop' tag="li"><i class="el-icon-shopping-cart-full"></i><span>购物车</span></router-link>
        <router-link to='/my' tag="li"><i class="el-icon-user-solid"></i><span>我的</span></router-link>
    </div>
</template>
<style>
.tabBar{
    width: 16rem;
    height: 2rem;
    position: fixed;
    bottom: 0;
    border-top:1px solid #e5e5e5;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
li{
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 0.8rem;
}
.router-link-exact-active{
    color: #f40;
}
</style>