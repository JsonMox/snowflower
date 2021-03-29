<template>
    <div id="CompanyIntroduction">
        <div class="banner container-fuild text-center">关于我们</div>
        <div class="container">
            <div class="row CompanyIntroduction-container">
                <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">
                    <img class="img-responsive center-block" src="@/assets/img/about_img.png">
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6">
                    <h2>北京金睛云华有限公司</h2>
                    <h4>关于金睛云华</h4>
                    <p class=".text-justify">北京金睛云华科技有限公司成立于2016年，注册资本金为1372万元人民币, 融资金额超过5000万。公司以“ AI驱动安全”为核心理念, 持续研发基于大数据人工智能技术的新一代网络安全产品, 包括高级威胁检测系统（ATD）、全流量回溯分析取证系统（TFS）、APT智能沙箱系统（AIS）、恶意加密流量检测系统（MED）、大数据安全分析与态势感知系统（CIC）、大数据威胁情报系统（CTI）、主机威胁取证系统（HTD）。目前已拥有十多项基于人工智能的安全技术专利，所服务的客户已超过500个，现网运行的系统已超过3000套，客户遍及公安、军队、金融、运营商、广电、政府、能源、电力、企业和高校等多个行业。</p>
                    <h4>我们的团队</h4>
                    <p class=".text-justify">创始人及核心团队来自华为、启明星辰和东软, 首席科学家由著名的网络安全专家谭晓生担任。 公司团队在网络安全和人工智能领域有十余年的研究经验和技术积累, 并拥有十多项基于人工智能的网络安全检测专利。</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
    name: 'CompanyIntroduction',
    data(){
        return{

        }
    },
    mounted(){
        var wow = new WOW();
        wow.init();
    }
}
</script>
<style scoped>
.banner{
    color: #fff;
    font-size: 30px;
    height: 150px;
    line-height: 150px;
    background-image: url('../assets/img/banner1.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: scroll;
    background-position: center center;
}
.row{
    margin-right: 0;
    margin-left: 0;
}
.CompanyIntroduction-container{
    padding: 100px 0;
    color: #808080;
    transition: all ease 0.5s;
}
.CompanyIntroduction-container>div>p{
    font-size: 14px;
    line-height: 2.5rem;
}
@media screen and (max-width: 997px){
    .CompanyIntroduction-container{
    padding: 10px 0;
    color: #808080;
}
}
</style>

