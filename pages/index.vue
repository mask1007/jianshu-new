<template>
    <div style="height: 100%;">
        <my-header></my-header>
        <div class="container index">
            <div class="row">
                <!--占16份-->
                <div class="col-xs-16 main">
                    <!--热门专题-->
                    <div class="recommend-collection">
                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~assets/img/c1.jpg">
                            <span name="name">手绘</span>
                        </nuxt-link>

                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~assets/img/c2.jpg">
                            <span name="name">读书</span>
                        </nuxt-link>

                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~assets/img/c3.jpg">
                            <span name="name">社会热点</span>
                        </nuxt-link>

                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~assets/img/c4.jpg">
                            <span name="name">@IT·互联网</span>
                        </nuxt-link>

                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~assets/img/c1.jpg">
                            <span name="name">旅行·在路上</span>
                        </nuxt-link>

                        <nuxt-link class="collection" to="/collection/123">
                            <img src="~assets/img/c2.jpg">
                            <span name="name">历史</span>
                        </nuxt-link>
                        <nuxt-link to="/collection/123" class="more-collection">
                            更多热门专题
                            <i class="fa fa-angle-right"></i>
                        </nuxt-link>
                    </div>
                    <div class="split-line"></div>
                    <!--文章列表-->
                    <div class="list-container">
                        <ul class="note-list">
                            <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~assets/img/note.jpg">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="'/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">04.12 10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">农夫山泉有点甜</nuxt-link>
                                    <div class="abstruct">
                                        忽然觉得最近某个朋友热情起来了。微信里朋友圈开始点赞打招呼了，从不关注我孩子的，居然也问起我的孩子来了。过来喝茶时带着小吃，笑容可掬，春风满面，让人心里暖暖的。就是嘛，我是...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>

                                    </div>
                                </div>

                            </li>
                            <li>

                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="'/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">04.12 10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">农夫山泉有点甜</nuxt-link>
                                    <div class="abstruct">
                                        忽然觉得最近某个朋友热情起来了。微信里朋友圈开始点赞打招呼了，从不关注我孩子的，居然也问起我的孩子来了。过来喝茶时带着小吃，笑容可掬，春风满面，让人心里暖暖的。就是嘛，我是...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>

                                    </div>
                                </div>
                            </li>
                            <li class="have-img">
                                <nuxt-link to="/p/123" class="wrap-img">
                                    <img src="~assets/img/note.jpg">
                                </nuxt-link>
                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="'/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">04.12 10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">农夫山泉有点甜</nuxt-link>
                                    <div class="abstruct">
                                        忽然觉得最近某个朋友热情起来了。微信里朋友圈开始点赞打招呼了，从不关注我孩子的，居然也问起我的孩子来了。过来喝茶时带着小吃，笑容可掬，春风满面，让人心里暖暖的。就是嘛，我是...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/c/123" class="collection-tag">社会与法</nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>

                                    </div>
                                </div>

                            </li>
                            <li>

                                <div class="content">
                                    <div class="author">
                                        <nuxt-link to="/p/123" class="avatar">
                                            <img src="~assets/img/default-avatar.jpg">
                                        </nuxt-link>
                                        <div class="info">
                                            <nuxt-link to="'/u/123" class="nickname">测试用户</nuxt-link>
                                            <span class="time">04.12 10:18</span>
                                        </div>
                                    </div>
                                    <nuxt-link class="title" to="/p/123">农夫山泉有点甜</nuxt-link>
                                    <div class="abstruct">
                                        忽然觉得最近某个朋友热情起来了。微信里朋友圈开始点赞打招呼了，从不关注我孩子的，居然也问起我的孩子来了。过来喝茶时带着小吃，笑容可掬，春风满面，让人心里暖暖的。就是嘛，我是...
                                    </div>
                                    <div class="meta">
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-eye"></i>
                                            1500
                                        </nuxt-link>
                                        <nuxt-link to="/p/123">
                                            <i class="fa fa-comment"></i>
                                            100
                                        </nuxt-link>
                                        <span>
                                            <i class="fa fa-heart"></i>
                                            20
                                        </span>

                                    </div>
                                </div>
                            </li>
                        </ul>
                        <a href="#" class="load-more">阅读更多</a>
                    </div>
                </div>
                <!--占7份，偏移了1份-->
                <div class="col-xs-offset-1 col-xs-7 aside">
                    侧边栏
                </div>
            </div>
        </div>


    </div>
</template>
<script>
    //导入组件
    import myHeader from '../components/myHeader'

    export default {
        head: {
            title: '简书-创作你的创作',
            meta: [
                {charset: 'utf-8'},
                {name: 'keywords', content: '简书首页'},
                {name: 'description', content: '简书首页'},
                {name: 'author', content: '孔露萍'}
            ]
        },
        //把组件写进来
        components: {
            myHeader
        },
        data() {
            return {
                name: '首页'
            }
        }
    }
</script>
<style>

</style>