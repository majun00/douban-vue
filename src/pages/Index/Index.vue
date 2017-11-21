<template>
  <div>
    <m-header title="豆瓣app" :bg="true" fixed>
	  <a href="javascript:;" slot="left"><img class="m-icon-img" src="../../assets/images/ic_bar_back_white.png"/>返回</a>
	  <a href="javascript:;" slot="right">分享</a>
    </m-header>
  </div>
</template>

<script>
  import mHeader from '../../components/header'

  export default {
    name: 'index',
    components: {
      mHeader
    }
  }
</script>