<template>
    <div>
        <my-header></my-header>
    </div>
</template>

<script>
    import myHeader from '~/components/myHeader'
    export default {
        head:{
            title:'简书文章喜欢和赞页面',
            meta:[
                {charset:'utf-8'},
                {name:'keyword',content:'文章喜欢和赞'},
                {name:'description',content:'文章喜欢和赞页面'}
            ]
        },
        data(){

        },
        components:{
            myHeader
        }
    }
</script>

<style scoped>

</style>