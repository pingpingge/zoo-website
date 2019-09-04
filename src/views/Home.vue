<template>
  <div class="home">
    <heads></heads>
    <div style="width:100%;height:100%">
      <div style="width:100%;height:724px;background:#ccc">
      <div style="width:100%;height:329px;background:skyblue"> 
        <div style="width:987px;height:284px;background:green;margin:auto">

        </div>
      </div>
      </div>
    </div>
    <foot></foot>
  </div>
</template>

<script>
// @ is an alias to /src
import heads from '@/components/header.vue'
import foot from '@/components/footer.vue'


export default {
  name: 'home',
  components: {
    heads,
    foot
  }
}
</script>
<style lang="less" scoped>

</style>
