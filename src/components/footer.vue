<template>
    <div class="footer" style="background:#515151 ;width:100%">
        <div style="width:1142px;height:415px;margin:0 auto;">
            <div class="logo">
                <div class="logo-img">
                   <img src="../assets/hxzlogo.png" alt="" style="width:100%;height:100%">
                </div>
            </div>
            <div class="mid" style="height:200px;width:100%;margin-top:22px">
                <div class="code" style="height:200px;width:234px;float:left;margin-right:147px;">
                   <div style="font-size:21px;color:#fff;  ">北京雪族科技有限公司</div>
                   <div style="margin-top:22px;height:136px">
                       <div style=" float:left;">
                           <img src="../assets/erweima.png" alt="" style="width:77px;height:77px">
                           <p style="color:#fff">关注微信</p>
                       </div>
                       <div style=" float:right;">
                           <img src="../assets/erweima.png" alt="" style="width:77px;height:77px">
                           <p style="color:#fff">扫码下载</p>
                           <p style="color:#fff">KIWI运动APP</p>
                       </div>
                   </div>
                   <div style="width:100%">
                       <p style="color:#fff;font-size:13px;">北京市西城区西直门南大街2号成铭大厦</p>
                   </div>
                </div>
                <div class="mid-mid">
                    <p style="font-size:16px;font-weight:bold">关于我们</p>
                    <p v-for="(item,index) in listone" :key=index style="font-size: 14px;line-height: 29px;">{{item}}</p>
                   
                </div>
                <div class="mid-right">
                    <p style="font-size:16px;font-weight:bold">产品服务</p>
                    <p v-for="(item,index) in listtwo" :key=index style="font-size:14px;line-height: 29px;">{{item}}</p>
                </div>
                <div class="mid-r">
                    <p style="font-size:16px;font-weight:bold">联系我们</p>
                    <p v-for="(item,index) in listthree" :key=index style="font-size: 14px;line-height: 29px;">{{item}}</p>
                </div>

            </div>
            <div class="bt" style="height:44px;width:267px;text-algin:center;font-size:12px;color:#fff;margin:36px auto">
                <p>Copyright©2014 北京滑雪科技有限公司 版权所有</p>
                <p>京ICP备1404257号-1</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
       name:"foot",
       data(){
           return{
               listone:['公司介绍','荣誉奖项','成功案列'],
               listtwo:['iSNOW冰雪企业云服务','滑雪族','KIWI运动','ICE MINI','硬件设备'],
               listthree:['联系电话：010-84549822','SNOW：wujiaming@huaxuezoo.com','HIGHSNOW:hujing@huaxuezoo.com','ICEMINI:hujing@huaxuezoo.com','友情链接：快递查询']
           }
       } 
    }   
</script>

<style>
.logo{
    width:100%;
    height:80px;
   
}
.logo-img{
    width: 182px;
    height: 54px;
    float: left; 
    margin-top: 26px;
}
.mid-mid{
    height:200px;
    width:66px;
    color:#EEEEEE;
    float: left;
    /* margin-left:147px； */
}
.mid-right{
    height: 200px;
    width: 148px;
    text-align: left;
    float:left;
    margin-left: 182px;
    color:#EEEEEE;
}
.mid-r{
    width: 238px;
    text-align: left;
    color:#EEEEEE;
    float:right;
    
}
</style>