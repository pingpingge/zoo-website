<template>
  <div style="width:100%;height:86px;background:#14A1DC">
    <div style="width:1142px;margin:0 auto;height:86px;line-height:86px;">
      <div style="float: left;width:164px;height:86px;margin-right:10px" >
        <img src="../assets/huaxuezooLOGO.png" alt="" style="width:100%;height:48px;vertical-align: middle">
      </div>
      <div style="float:left;height:86px;line-height:86px;">
        <ul >
          <li v-for="(item,index) in navlist" :key=index style="float: left;font-size: 22px;margin:0 30px;">{{item}}</li>
        </ul>
      </div>
      

	</div>
      
    
  </div>
</template>


<script type="text/javascript">
export default {
  name:'heads',
  data() {
    return {
      navlist:['首页','ISNOW','滑雪族','ICEMINI','KIWI运动','渠道合作','关于我们']
    };
  },
  methods: {
   
  
  }
}
</script>

<style scoped>

</style>
