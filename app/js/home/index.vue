<template lang="html">
    <div :class="$style.home">
        <h1>Home</h1>
        
    </div>
    
</template>

<script>
import btn from '../core/btn'
export default {
  components:{
    btn
  }
}
</script>

<style lang="scss" module>
  @import '../../css/reset.scss';
  .home{
    color: red;
    font-size: 80px;
  }
</style>
