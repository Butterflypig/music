<template>
    <div>
        <div class="top-bg">
            <div class="top-menu">
                <div>&lt;</div>
                <div>注册</div>
            </div>
        </div>
        <div class="botton">
            <div class="content">
                <div>
                    <input type="text" value="" placeholder="用户名/手机号/邮箱">
                </div>
                <div>
                    <input type="password" value="" placeholder="请输入密码">
                </div>
                <div>
                    <button>登录</button>
                </div>
                <div class="forget" align="right">
                    <span>忘记密码?</span>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .top-bg{
        width: 100%;
        height: 333px;
        background-color: #408080;
    }
    .top-menu{
        color: #fff;
        display: flex;
        flex-flow: row nowrap;
        justify-content: space-between;
        font-size: 14px;
    }
    .top-menu > div{
        margin-top: 20px;
        padding: 10px;
    }

    /* 下半部 */
   .botton{
        position: relative;
        top: -50px;
   }
   .content{
        margin: 0 auto;
        width: 88%;
        height: 333px;
        background-color: #fff;
        box-shadow: 0 0 3px lightgrey;
   }
   .content input{
       width: 80%;
       height: 30px;
       border: none;
       border-bottom: 1px solid lightgrey; 
       outline: none;
       margin-top: 20px; 
   }
   .content button{
       width: 80%;
       margin-top: 40px;
       padding: 10px;
       border-radius: 15px;   
       border: none;
       outline: none;
       font-size: 18px;
       color: #fff;
       background-color: rgb(114, 194, 245);
   }
   .forget{
       margin-top: 20px;
       font-size: 12px;
   }
   .forget > span{
       margin-right: 40px; 
       color: rgb(114, 194, 245);
   }
</style>
