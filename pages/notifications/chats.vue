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
                        <div class="menu">全部简信</div>
                        <ul class="jianxin-list">
                            <li>
                                <div class="pull-right">
                                    <span class="time">04.26 22.53<i class="fa fa-chevron-down"></i>
                                        </span>
                                    <div>


                                    </div>
                                </div>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/default-avatar.gif">
                                    <span class="badge">1</span>
                                </a>
                                <a href="/u/123" class="name">茶点故事</a>
                                <a href="/notifications/chats/123" class="wrap">
                                    <p>Hi,很高兴可以跟你一起开启简书历史上最特别的篇章“423简书故事节”。来看看我们为你准备的...</p>
                                </a>
                            </li>
                            <li>
                                <div class="pull-right">
                                    <span class="time">10.07 10.07<i class="fa fa-chevron-down"></i>
                                        </span>
                                    <div>


                                    </div>
                                </div>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/default-avatar.jpg">
                                    <span class="badge">1</span>
                                </a>
                                <a href="/u/123" class="name">简宝玉</a>
                                <a href="/notifications/chats/123" class="wrap">
                                    <p> 欢迎加入丰富多彩的原创内容社区—简书。新手有关简书的任何疑问请点击链接查看 http://w...</p>
                                </a>
                            </li>
                            <li>
                                <div class="pull-right">
                                    <span class="time">04.08 12.25<i class="fa fa-chevron-down"></i>
                                        </span>
                                    <div>


                                    </div>
                                </div>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/2.jpg">
                                    <span class="badge">2</span>
                                </a>
                                <a href="/u/123" class="name">小简姑娘</a>
                                <a href="/notifications/chats/123" class="wrap">
                                    <p>读过仓央嘉措活佛的一本书，叫做 一切都是最好的安排，我对这句话深信不疑，如果不是最好...</p>
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
        head: {
            title: '简书文章简信页面',
            meta: [
                {charset: 'utf-8'},
                {name: 'keyword', content: '文章简信'},
                {name: 'description', content: '文章简信页面'}
            ]
        },
        data() {

        },
        components: {
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

    .notification .main ul {
        list-style: none;
        padding-left: 0;
    }
    .notification .main .jianxin-list li{
        position: relative;
        border-top: 1px solid #f0f0f0;
        line-height: 20px;
    }

    .notification .main .jianxin-list .pull-right {
        margin: 20px 20px 0 0;
        font-size: 13px;
        float: right !important;
    }
    .notification .main .jianxin-list .pull-right .time{
        color: #9b9b9b;
    }
    .notification .main .jianxin-list .avatar{
        float: left;
        margin: 20px 10px 20px 20px;
        width: 48px;
        height: 48px;
    }
    .notification .main .jianxin-list .badge{
        position: relative;
        float: right;
        top: -52px;
        right: -5px;
        padding: 3px 6px;
        font-size: 13px!important;
        background-color: #ea6f5a;
        display: inline-block;
        min-width: 10px;
        font-weight: 700;
        color: #fff;
        line-height: 1;
        vertical-align: middle;
        white-space: nowrap;
        text-align: center;
        border-radius: 10px;
    }
    .notification .main .jianxin-list .name{
        position: absolute;
        top: 25px;
        font-size: 15px;
    }
    .notification .main .jianxin-list .wrap{
        display: block;
        padding: 20px 20px 20px 0;
        min-height: 88px;
    }
    .notification .main .jianxin-list p{
        margin: 28px 0 0;
        font-size: 12px;
        color: #999;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
    }
</style>