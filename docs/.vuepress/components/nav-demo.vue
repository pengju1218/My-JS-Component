<template>
    <div  class="nav">
        <div class="nav-item" >首页</div>
        <div class="sub-nav">
            <span class="sub-nav-label">关于</span>
            <div class="sub-nav-popover">
                <div  class="nav-item" >企业文化</div>
                <div  class="nav-item" >开发团队</div>
                <div  class="sub-nav">
                    <span class="sub-nav-label">联系方式</span>
                    <div  class="sub-nav-popover">
                        <div class="nav-item">微信</div>
                        <div class="nav-item">QQ</div>
                        <div class="sub-nav">
                            <span class="sub-nav-label">手机</span></span>
                            <div  class="sub-nav-popover">
                                <div class="nav-item" >移动</div>
                                <div class="nav-item" >联通</div>
                                <div class="nav-item" >电信</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="nav-item">招聘</div>
    </div>

</template>
<script>
    import '../../../dist/magicUI.js'
    export default{
        mounted(){
            let nav = new Nav(".nav")
        }
    }
</script>

<style lang="scss">
</style>
