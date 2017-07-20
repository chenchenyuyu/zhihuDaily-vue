<div class="list-header">
  <ul class="ul-list">
    <li><img src="../assets/images/Category.png" alt="icon"></li>
    <li class="home"><span>首页</span></li>
    <li><img src="../assets/images/remind.png" alt="icon"></li>
    <li><img src="../assets/images/browse.png" alt="icon"></li>
  </ul>
</div>
<script>
  export default {

  }
</script>
<style lang="scss">
  .main-list{
    position: fixed;
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    top: 0;
    z-index: 4;
    height: 12%;
    width: 100%;
    background: #00a2ea;
  }
  .ul-list li{
    display: inline-block;
    margin:1%;
  }
  .ul-list .home span{
    margin-right:18%;
    color:#fff;
  }

</style>
