<template>
  <div id="container">
    <a-row class="header">
        <a-col :sm="24" :xl="9">🐌蜗牛骑行</a-col>
        <a-col :sm="24" :xl="15">
            <a-space :size="3">
                <a-button type="link" class="button-font">基本资料</a-button>
                    <a-button type="link" class="button-font">项目经验</a-button>
                    <a-button type="link" class="button-font">专业技能</a-button>
                    <a-button type="link" class="button-font">工作经历</a-button>
                    <a-button type="link" class="button-font">自我评价</a-button>
                    <a-button type="link" class="button-font">联系方式</a-button>
            </a-space> 
        </a-col>
    </a-row>
    <a-layout>
        <a-layout-header class="banner">
            <div class="title">简历-xxx</div>
            <div class="desc">喜欢技术,热爱挑战!!!</div>
            <a-button ghost="true" shape="circle" icon="arrow-down" :size="large"/>
        </a-layout-header>
        <a-layout-content>
            <a-row class="jibenziliao"> 
                <a-row>
                    <div class="subtitle">
                        <h2>基本 资料</h2>
                    </div>
                </a-row>
                <a-row type="flex" justify="center">
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                               <a-icon type="pause-circle" style="fontSize: 100px"/>
                            </div>
                            <div class="childtitle">个人信息</div>
                            <div class="childdesc">英文名: Baron  性别：男 年龄: 25岁 籍贯：湖南</div>
                        </div>
                    </a-col>
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                                <a-icon type="copyright" style="fontSize: 100px"/>
                            </div>
                            <div class="childtitle">专业学历</div>
                            <div class="childdesc">专业：电子信息工程 学历：大学本科</div>
                        </div>
                    </a-col>
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                                <a-icon type="global"  style="fontSize: 100px"/>
                            </div>
                            <div class="childtitle">毕业院校</div>
                            <div class="childdesc">毕业学校：xx理工大学 学习技能：编程</div>
                        </div>
                    </a-col>
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                                <a-icon type="wechat" style="fontSize: 85px"/>
                            </div>
                            <div class="childtitle">联系方式</div>
                            <div class="childdesc">QQ：xxx 邮箱：xxx</div>
                        </div>
                    </a-col>
                </a-row>
            </a-row>
            <a-row class="project"> 
                <a-row>
                    <div class="subtitle">
                        <h2 style="color: inherit;font-size: 30px">项目 经验</h2>
                    </div>
                </a-row>
                <a-row>
                    <div>
                        <div>主要涉及电商，金融，家装领域，包括PC端，手机端，微信端，移动APP端等等，主要技术是HTML+CSS+JS</div>
                    </div>
                </a-row>
                <a-row>
                    <a-card bordered="true">
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-01.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-02.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-01.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-02.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-01.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-02.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-01.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                        <a-card-grid style="width:25%;text-align:center">
                            <a-card>
                                <img height="200" width="100" 
                                    slot="cover"
                                    alt="example"
                                    src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/project-02.jpg"
                                    />
                            </a-card>
                        </a-card-grid>
                    </a-card>
                </a-row>
            </a-row>
            <a-row class="zhuanyejineng"> 
                <a-row>
                    <div class="subtitle">
                        <h2 style="color: inherit;font-size: 30px">专业 技能</h2>
                    </div>
                </a-row>
                <a-row>
                    <a-col :span="12">
                        <div style="margin-bottom: 80px">
                            <img src="https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/zhuanyejineng.png"/>
                        </div>
                     </a-col>
                    <a-col :span="12">
                        <a-descriptions title="PC端">
                            <a-descriptions-item>
                                熟练使用HTML/CSS技术，精通Javascript/jquery编程,能够熟练使用angularjs，reactjs等前端MVC框架进行模块开发，熟练的使用grunt，gulp等前端工具，了解less，sass，stylus，coffeescript等前端新技术
                            </a-descriptions-item>
                        </a-descriptions>
                        <a-descriptions title="移动端">
                            <a-descriptions-item>
                                熟练使用zepto.js，Frozen ui，Amaze ui等移动框架进行移动页面的开发，熟练使用threejs等js引擎进行3d效果和H5游戏的开发.
                            </a-descriptions-item>
                        </a-descriptions>
                         <a-descriptions title="其它">
                            <a-descriptions-item>
                                懂网站性能优化，网站百度排名和SEO优化，熟练使用photoshop等切图工具，会常见的UI技巧，懂Java，php等后台语言开发.
                            </a-descriptions-item>
                        </a-descriptions>
                    </a-col>
                </a-row>
            </a-row>
            <a-row class="renshengjingli"> 
                <a-row>
                    <div class="subtitle">
                        <h2>人生 经历</h2>
                    </div>
                </a-row>
                <a-row type="flex" justify="center">
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                               <a-icon type="pause-circle" style="fontSize: 100px"/>
                            </div>
                            <div class="childtitle">个人信息</div>
                            <div class="childdesc">英文名: Baron  性别：男 年龄: 25岁 籍贯：湖南</div>
                        </div>
                    </a-col>
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                                <a-icon type="copyright" style="fontSize: 100px"/>
                            </div>
                            <div class="childtitle">专业学历</div>
                            <div class="childdesc">专业：电子信息工程 学历：大学本科</div>
                        </div>
                    </a-col>
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                                <a-icon type="global"  style="fontSize: 100px"/>
                            </div>
                            <div class="childtitle">毕业院校</div>
                            <div class="childdesc">毕业学校：xx理工大学 学习技能：编程</div>
                        </div>
                    </a-col>
                    <a-col :span="4">
                        <div align="center">
                            <div class="circle">
                                <a-icon type="wechat" style="fontSize: 85px"/>
                            </div>
                            <div class="childtitle">联系方式</div>
                            <div class="childdesc">QQ：xxx 邮箱：xxx</div>
                        </div>
                    </a-col>
                </a-row>
            </a-row>
            <a-row class="renshengjingli-banner"> 
                <a-row>
                    <div class="subtitle">
                        <h2>自我 评价</h2>
                    </div>
                    <div align="center">
                        <div style="width: 550px; font-size: 20px; color: #DDDDDD;margin-top: 100px">
                            热爱学习,良好的团队合作精神，能迅速融入新的团队。易和人相处，拥有良好的亲和力。
                        </div>
                    </div>
                </a-row>
            </a-row>
            <a-row class="lianxifangshi"> 
                <a-row>
                    <div class="subtitle">
                        <h2 style="color: black">给我发邮件</h2>
                    </div>
                    <div>
                        <a-row type="flex" justify="space-around">
                            <a-col :span="4">
                                <a-input style="width: 400px" placeholder="邮箱" />
                            </a-col>
                            <a-col :span="4" :pull="3">
                                <a-input style="width: 400px" placeholder="姓名" />
                            </a-col>
                        </a-row>
                    </div>
                </a-row>
            </a-row>
        </a-layout-content>
        <a-layout-header style="color: whitesmoke">Copyright © 2020</a-layout-header>
    </a-layout>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
/** header */
#container {
  text-align: center;
}

.button-font{
    color: #fff;
}

.header{ 
    background-color: black;
    line-height: 60px;
    color: whitesmoke;
}

.banner{
    background-image: url(https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/banner.jpg);
    height: 1000px;
}

.renshengjingli-banner{
    background-image: url(https://cdn.jsdelivr.net/gh/tsing-dong/drawing.bed/articleTopics/projectPractice/resume/banner.jpg);
    height: 600px;
}

.title {
    color: yellow;
    font-size: 70px;
    font-weight: 800;
    padding-top: 150px;
}

.desc{
    font-size: 20px;
    text-transform: uppercase;
    letter-spacing: 8px;
    margin-bottom: 50px;
}

.anniu{
    width: 90px;
}


/** content */
.jibenziliao {
    height: 495px;
    background: linear-gradient(to bottom right, rgb(73, 68, 68) , rgb(66, 59, 59)); /* 标准的语法 */
}

.childtitle{
    font-weight: bold;
    box-sizing: border-box;
    color: yellow;
    font-size: 18px;
}

.circle {
	width: 100px;
	height: 100px;
	-moz-border-radius: 50px;
	-webkit-border-radius: 50px;
	border-radius: 50px;
	background-color: #474b4f;
}

.subtitle{
    margin-top: 100px;
    margin-bottom: 60px;
    font-weight: 400;
    margin-bottom: 30px;
}

.childdesc{
    font-family: microsoft yahei, sans-serif;
    color: #aaa;
}

.subtitle > h2{
    font-weight: 400;
    margin-bottom: 30px;
    font-size: 40px;
    color: #ddd;
}

/* 专业技能 */
.zhuanyejineng{
    background-color: rgb(243,207,48);
}

.renshengjingli{
    background-color: rgb(241,241,241);
    margin-bottom: 200px;
    margin-top: 100px;
}

.lianxifangshi{
    padding-bottom: 200px;
}
</style>
