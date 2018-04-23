<template>
    <div style="height: 100%;">
        <my-header></my-header>
        <div class="container index">
            <div class="row">
                <!--占16份-->
                <div class="col-xs-16 main">
                    <!--热门专题-->
                    <div class="recommend-collection">
                    <nuxt-link class="collection"  to="/collection/123">
                        <img src="~assets/img/c1.jpg">
                        <span name="name">手绘</span>
                    </nuxt-link>

                    <nuxt-link class="collection"  to="/collection/123">
                        <img src="~assets/img/c2.jpg">
                        <span name="name">读书</span>
                    </nuxt-link>

                    <nuxt-link class="collection"  to="/collection/123">
                        <img src="~assets/img/c3.jpg">
                        <span name="name">社会热点</span>
                    </nuxt-link>

                    <nuxt-link class="collection"  to="/collection/123">
                        <img src="~assets/img/c4.jpg">
                        <span name="name">@IT·互联网</span>
                    </nuxt-link>

                    <nuxt-link class="collection"  to="/collection/123">
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