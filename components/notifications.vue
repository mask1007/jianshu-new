<template>
    <div>
        <ul>
            <li>
                <nuxt-link to="/notifications/comments">
                    <i class="fa fa-comment-o"></i>
                    评论
                </nuxt-link>
            </li>

            <li>
                <nuxt-link to="/notifications/chats">
                    <i class="fa fa-envelope-o"></i>
                    简信
                </nuxt-link>
            </li>

            <li>
                <nuxt-link to="/notifications/follows">
                    <i class="fa fa-plus-square-o"></i>
                    关注
                </nuxt-link>
            </li>

            <li>
                <nuxt-link to="/notifications/likes">
                    <i class="fa fa-heart-o"></i>
                    喜欢和赞
                </nuxt-link>
            </li>
        </ul>

    </div>

</template>

<script>
    export default {
        name: "notifications"
    }
</script>

<style>
    .notification .row {
        display: block;
        padding: 30px 0;
        margin-left: -15px;
        margin-right: -15px;
    }
    .notification .row .aside{
        display: inline-block;
    }

    .notification .row .aside ul li a {
        padding: 10px 20px;
        line-height: 30px;
        display: block;
    }

    .notification .row .aside ul li a:hover {
        background-color: #f0f0f0;
    }



    .notification .row .aside ul li a i {
        margin-right: 15px;
        color: #ea6f5a;
        width: 20px;
        height: 20px;
        font-size: 20px;
        display: inline-block;
    }


</style>