<template>
    <div id="sign-template">
        <nuxt/>
    </div>
</template>
<script>

    export default {

    }
</script>
<style>

    .sign{
        height: 100%;
        font-size: 14px;
        text-align: center;
        background-color: #f1f1f1;
        min-height: 750px;
    }
    .sign:before{
        content: "";
        display: inline-block;
        height: 85%;
        vertical-align: middle;

    }
    .sign img{
        width: 100px;
    }
    .sign .logo{
        position: absolute;
        left: 50px;
        top: 56px;
    }
    .sign .main{
        width: 400px;
        margin: 60px auto 0;
        padding: 50px 50px 30px;
        background-color: #fff;
        border-radius: 4px;
        box-shadow: 0 0 8px rgba(0,0,0,.1);
        display: inline-block;
        vertical-align: middle;
    }
    .sign .main .title{
        margin: 0 auto 30px;
        color: #939393;
        font-size: 18px;
    }
    .sign.mian h4 b{
        font-weight: 800;
        padding: 10px;
        color: #969696;
    }

    .sign .main h4 a {
        font-weight:bolder;
        padding: 10px;
        color: #969696;
    }
    .sign .main h4 a.active{
        font-weight: 700;
        color: #ea6f5a;
        border-bottom: 2px solid #ea6f5a;
    }
    .sign .main h4 a:hover{
        border-bottom: 2px solid #ea6f5a;
        color: #ea6f5a;
    }
    .sign .main form {
        color: #969696;
        margin: 0 0 30px;
    }
    .sign .main form .input-prepend{
        position: relative;
        width: 100%;
    }
    .sign .main form .input-prepend input{
        width: 100%;
        height: 50px;
        padding: 4px 12px 4px 35px;
        border: 1px solid #c8c8c8;
        border-radius: 2px;
        background-color: rgb(248,248,248);
    }
    .sign .main form .input-prepend:nth-of-type(1) input{
        border-bottom: 0;
        border-radius: 2px 0 0 2px;
    }
    .sign .main form .input-prepend:nth-child(2) input{
       border-radius:  0 0 2px 2px;
    }
    .sign .main form .input-prepend i{
        position: absolute;
        left: 15px;
        top: 15px;
        font-size: 20px;
        color: #969696;
    }
    .sign .main form .remember{
        float: left;
        margin: 20px  0;
    }
    .sign .main form .help{
        float: right;
        margin: 20px  0;
        color: #969696;
    }
    .sign .main form .help:hover{
        color: #333;
    }
    .sign .main form button{
        width: 100%;
        margin: 0px 0 0;
        padding: 9px 18px;
        text-align: center;
        color: #fff;
        background: #3194d0;
        border-radius: 25px;
        font-size: 18px;
        outline:none;
        border:none;
        clear: both;
    }
    .sign .main form button:hover{
        background-color:#187cb7;
    }
    .sign .main .more-sign p{
        position: relative;
        font-size: 14px;
        color: #b8b8b8;
    }
    .sign .main .more-sign p:before{
        content: '';
        width: 60px;
        border-bottom: 1px solid #b8b8b8;
        position: absolute;
        left: 30px;
        top: 10px;
        margin-bottom: 20px;
    }
    .sign .main .more-sign p:after{
        content: '';
        width: 60px;
        border-bottom: 1px solid #b8b8b8;
        position: absolute;
        right: 30px;
        top: 10px;
    }
    .sign .main .more-sign ul{
        margin-bottom: 10px;
    }
    .sign .main .more-sign ul li{
        display: inline-block;
        color: white;
        margin: 0 5px;
        border-radius: 50%;
    }
    .sign .main .more-sign ul li a{
        width: 50px;
        height: 50px;
        line-height: 50px;
        display: block;
    }
    .sign .main .more-sign ul li {
        font-size: 24px;
    }
    .sign .main .more-sign ul li a i.weixin{
        color: #00bb29;
    }
    .sign .main .more-sign ul li a i.weibo{

        color: #e05244;
    }
    .sign .main .more-sign ul li a i.qq{
        color: #498ad5;
    }





    @media  screen and (max-width: 768px){

    .sign{
        background-color: #fff;
    }
    .sign .logo{
        display: none;
    }
    .sign .main{
       box-shadow: none;
    }
    .sign:before{
        height: 0;
    }

}













</style>