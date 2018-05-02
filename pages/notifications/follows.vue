<template>
    <div>
        <my-header></my-header>
        <div class="container notification">
            <div class="row">
                <div class="col-xs-7 aside">
                    <notifications></notifications>
                </div>
                <div class="col-xs-16 col-xs-offset-1 main">
                    <div>
                        <div class="menu">全部关注</div>
                        <ul class="follow-list">
                            <li>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/2.jpg">
                                </a>
                                <div class="info">
                                    <a href="/u/123" class="user">我是张夫人啊</a>
                                   <span>关注了我</span>
                                    <div class="time">2018.05.04 08:28</div>
                                </div>
                                <a class="btn btn-success follow">
                                    <i class="fa fa-plus"></i>
                                    <span>关注</span>
                                </a>
                            </li>
                            <li>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/default-avatar.jpg">
                                </a>
                                <div class="info">
                                    <a href="/u/123" class="user">加猫儿x</a>
                                    <span>关注了我</span>
                                    <div class="time">2018.05.02 08:28</div>
                                </div>
                                <a class="btn btn-success follow">
                                    <i class="fa fa-plus"></i>
                                    <span>关注</span>
                                </a>
                            </li>
                            <li>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/default-avatar.gif">
                                </a>
                                <div class="info">
                                    <a href="/u/123" class="user">一颗甜菜呀-</a>
                                    <span>关注了我</span>
                                    <div class="time">2018.05.04 08:28</div>
                                </div>
                                <a class="btn btn-success follow">
                                    <i class="fa fa-plus"></i>
                                    <span>关注</span>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import Notifications from "../../components/notifications";
    import myHeader from '~/components/myHeader'
    export default {
        head:{
            title:'简书文章关注页面',
            meta:[
                {charset:'utf-8'},
                {name:'keyword',content:'文章关注'},
                {name:'description',content:'文章关注页面'}
            ]
        },
        data(){

        },
        components:{
            myHeader,
            Notifications

        }
    }
</script>

<style scoped>
    .notification .main .menu {
        margin-bottom: 20px;
        font-size: 14px;
        font-weight: 700;
    }
    .notification .main ul{
        list-style: none;
        padding-left: 0;
    }
    .notification .main .follow-list li{
        padding: 20px;
        border-top: 1px solid #f0f0f0;
        line-height: 20px;
    }
    .notification .main .follow-list .avatar{
        display: inline-block;
        margin-right: 5px;
        width: 40px;
        height: 40px;
        cursor: pointer;
    }
    .notification .main .follow-list .avatar img{
        width: 100%;
        height: 100%;
        border: 1px solid #ddd;
        border-radius: 50%;
        vertical-align: middle;
    }
    .notification .main .follow-list .info{
        max-width: 280px;
        display: inline-block;
        vertical-align: top;
        width: 535px;
        line-height: 1.7;
    }
    .notification .main .follow-list .info .user{
        margin: 0 5px 0 0;
        color: #333;
        font-size: 15px;
    }
    .notification .main .follow-list .info span{
        font-size: 15px;
    }
    .notification .main .follow-list .time{
        margin-top: -2px;
        font-size: 12px;
        color: #969696;
        line-height: normal;
    }
    .notification .main .follow-list .btn{
        display: inline-block;
        margin-bottom: 0;
        padding: 8px 0;
        width: 100px;
        float: right;
        font-size: 15px;
        border-color: #42c02e;
        font-weight: 400;
        line-height: normal;
        border-radius: 40px;
        color: #fff;
        background-color: #42c02e;
        text-align: center;
        vertical-align: middle;
        touch-action: manipulation;
        cursor: pointer;
        background-image: none;
        border: 1px solid transparent;
        white-space: nowrap;

    }
</style>