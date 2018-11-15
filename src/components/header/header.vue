<template>
    <header id='head_top'>
         <!--<section class="head_goback">
             <svg width="100%" height="100%" xmlns="http://www.w3.org/2000/svg" version="1.1">
                 <polyline points="12,18 4,9 12,0" style="fill:none;stroke:rgb(255,255,255);stroke-width:2"/>
             </svg>
        </section>-->
        <div>
            
        </div>
    </header>
</template>
<script>
    export default {
        data() {
            return {

            }
        }
    }
</script>
<style lang="scss">
    @import '../../style/mixin';

    #head_top{
        background-color: $blue;
        position: fixed;
        z-index: 100;
        left: 0;
        top: 0;
        @include wh(100%, 1.95rem);
    }
</style>