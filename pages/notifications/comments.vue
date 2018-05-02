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
                        <div class="menu">收到的评论</div>
                        <ul class="comment-list">
                            <li>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/default-avatar.gif"/>
                                </a>
                                <div class="info">
                                    <div>
                                        <a class="user" href="/u/123">超甜汽水音</a>
                                        <span class="comment-slogan">评论了你的文章</span>
                                        <a href="/p/123">《wy反黑组》</a>
                                    </div>
                                    <div class="time">2018.04.08 10.07</div>
                                </div>
                                    <p>xxj不用上课，这么闲吗</p>
                                    <div class="meta">
                                        <a class="function-btn">
                                            <i class="fa fa-comment-o"></i>
                                            <span>回复</span>
                                        </a>
                                        <a href="/p/123" class="function-btn">
                                            <i class="fa fa-mail-forward"></i>
                                            <span>查看对话</span>
                                        </a>
                                    </div>

                            </li>
                            <li>
                                <a href="/u/123" class="avatar">
                                    <img src="~assets/img/default-avatar.jpg"/>
                                </a>
                                <div class="info">
                                    <div>
                                        <a class="user" href="/u/123">甜菜除草大队</a>
                                        <span class="comment-slogan">评论了你的文章</span>
                                        <a href="/p/123">《wy反黑组》</a>
                                    </div>
                                    <div class="time">2018.04.08 10.07</div>
                                </div>
                                <p>抱紧央视爸爸的大腿</p>
                                <div class="meta">
                                    <a class="function-btn">
                                        <i class="fa fa-comment-o"></i>
                                        <span>回复</span>
                                    </a>
                                    <a href="/p/123" class="function-btn">
                                        <i class="fa fa-mail-forward"></i>
                                        <span>查看对话</span>
                                    </a>
                                </div>

                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    // import notifications from '~/components/notifications'
    import myHeader from '~/components/myHeader'
    import Notifications from "../../components/notifications";

    export default {
        head: {
            title: '简书文章评论页面',
            meta: [
                {charset: 'utf-8'},
                {name: 'keyword', content: '文章评论'},
                {name: 'description', content: '文章评论页面'}
            ]
        },
        data() {

        },
        components: {
            Notifications,
            myHeader
        }
    }
</script>

<style>
    .notification .main .menu {
        margin-bottom: 28px;
        font-size: 14px;
        font-weight: 700;
    }

    .notification .main ul {
        list-style: none;
        padding-left: 0;
    }
    .notification .main .comment-list li{
        padding: 20px;
        border-top: 1px solid #f0f0f0;
        line-height: 20px;

    }
    .notification .main .comment-list .avatar{
        display: inline-block;
        margin-right: 5px;
        width: 40px;
        height: 40px;
    }
    .notification .main .comment-list .info{
        display: inline-block;
        vertical-align: top;
        /*font-size: 0;*/
        line-height: 1.7;
    }
    .notification .main .comment-list .info .user{
        margin: 0 5px 0 0;
        color: #333;
        font-size: 15px;
    }
    .notification .main .comment-list .info span{
        font-size: 15px;
        color: #333;
    }
    .notification .main .comment-list .info a{
        font-size: 15px;
        color: #3194d0;
    }
    .notification .main .comment-list .time{
        /*margin-top: 2px;*/
        font-size: 12px;
        color: #969696;
        line-height: normal;
    }
    .notification .main .comment-list p{
        margin: 10px 0 0;
        font-size: 15px;
        line-height: 1.7;
    }
    .notification .main .comment-list .meta{
        margin-top: 10px;
        height: 20px;
    }
    .notification .main .comment-list .function-btn{
        float: left;
        margin-right: 30px;
        font-size: 13px;
        color: #969696;
    }
    .notification .main .comment-list .function-btn i{
        margin-right: 5px;
        font-size: 15px;
        vertical-align: middle;
    }
</style>