<style type="text/css" rel="stylesheet">
.hidden-td {
	border-style:none;
}
.content-td {
	padding-left:35px;
	font-size:13px;
	border-style:none;
	padding-bottom: 15px;
}
.project-header{
	text-align:center;
	font-weight:bold;
}
.project-content{
	/* font-size:14px; */
}
.project-item{
	text-align: right;
}
h2:not(#first-h2){
	padding-top: 25px;
}
</style>

<h2 id="first-h2"> 个人信息 </h2>

 <img src="assets/header-image.jpeg" width="130px" style="float:right;margin-top:0px;margin-right:100px;border-style:solid;
    border-width:0.5px;">
 - 姓名：董晓明
 - 出生年月：1995.12
 - 电话：17612409510
 - 邮箱：dongxiaoming01@foxmail.com
 - 求职意向：高级Java研发工程师

## 教育经历
<table style="width: 100%;table-layout: fixed;">
<tr>
	<td class="hidden-td"><li> 2013.09至2017.07</td>
	<td class="hidden-td">江南大学（211），轻化工程</td>
	<td class="hidden-td">本科</td>
</tr>
</table>

## 工作经历
<table style="width: 100%;table-layout: fixed;">
<tr>
	<td class="hidden-td"><li> 2022.04至今</td>
	<td class="hidden-td">北京广通优云有限公司</td>
	<td class="hidden-td">开发经理</td>
</tr>
<tr>
	<td colspan="3" class="content-td">交通银行数据中心生产运维一体化项目，负责开发管理、方案设计、核心功能开发；</td>
</tr>
<tr>
	<td class="hidden-td"><li> 2020.03至2022.04</td>
	<td class="hidden-td">万达信息</td>
	<td class="hidden-td">高级Java开发工程师</td>
</tr>
<tr>
	<td colspan="3" class="content-td">负责浙江省、上海市社区矫正项目的功能开发工作；</td>
</tr>
<tr>
	<td class="hidden-td"><li> 2018.02至2020.02</td>
	<td class="hidden-td">沈阳利达微科技有限公司</td>
	<td class="hidden-td">Java开发工程师</td>
</tr>
</table>

## 资格证书

- PMP认证
- RHCE认证（红帽Linux认证）

## 自我评级
1. 6年Java开发经验，熟练使用Jvm调优、Spring全家桶、Dubbo、Mysql、Redis、Kafka、
Es、Lua、Python自动化测试等，对系统架构设计具备一定理解；
2. 2.5年IT运维开发经验，对自动化运维、生产操作、CMDB、CI/CD等具有开发使用经验，
具备Shell脚本、Python脚本、Playbook脚本、Groovy脚本、网络设备脚本自动化运维工具
开发经验，具备应用发布、应急处置、技术变更、巡检场景开发经验；
3. PMP证书，2年开发管理经验；
4. RHEC证书，具有Linux操作系统、Shell脚本、Ansible使用能力。

<div style="page-break-after:always"></div>

##  项目经历
<table>
<tr>
	<td class="project-header" colspan="2"> 交通银行数据中心生产运维一体化项目 </td>
</tr>
<tr>
	<td class="project-item" width='16%'>项目介绍：</td>
	<td class="project-content">作为数据中心核心运维系统，以配置管理、监控告警、操作自动化和核心，致力于生产故障 1 分钟发现、3 分钟响应、15 分钟解决的运维要求。<br>其中包括模块：配置管理、用户管理、服务共享、自动化底座、生产操作、
监控告警等</td>
</tr>
<tr>
	<td class="project-item">涉及技术：</td>
	<td class="project-content">Spring、Dubbo、Redis、Mysql、Ansible、Es、Mongodb、Zookeeper、Kafka</td>
</tr>
<tr>
	<td class="project-item">职责描述：</td>
	<td class="project-content">1、自动化底座应用发布脚本开发：脚本任务、传输任务、压缩解压等脚本，
并通过直取 Kafka 方式解决读取 Es 数据延迟问题；<br>
2、自动化底座网络脚本、大型机脚本执行功能；<br>
3、生产操作场景登录慢问题优化，时间由 25 秒优化至 5 秒；<br>
4、基础管理登录、鉴权接口、基于 Springsecurity 统一登录认证、多租户方
案；<br>
5、cookie 和 header 的 token 冲突导致异常登录、 内存溢出导致服务中断、 cpu
飙升等复杂问题的处理；<br>
6、CI/CD 流水线搭建、代码版本管理等<br>
7、生产操作场景开发方案设计、开发管理、迭代管理、自动化测试等工作。<br>
</td>
</tr>
</table><br/><br/><br/>

<table>
<tr>
	<td class="project-header" colspan="2"> 浙江省社区矫正接口平台 </td>
</tr>
<tr>
	<td class="project-item" width='16%'>项目介绍：</td>
	<td class="project-content">用于浙江、上海智慧矫正终端机接口调用，以及浙江社区矫正数据对接。</td>
</tr>
<tr>
	<td class="project-item">涉及技术：</td>
	<td class="project-content">SpringBoot+SpringSecurity+Redis+Docker</td>
</tr>
<tr>
	<td class="project-item">职责描述：</td>
	<td class="project-content">采用 SpringSecurity 做权限认证， 使用 docker 在测试环境实施部署。 累计调用
达 1.8 亿次。
</td>
</tr>
</table><br/><br/><br/>

<table>
<tr>
	<td class="project-header" colspan="2"> 浙江省社区矫正综合管理平台 </td>
</tr>
<tr>
	<td class="project-item" width='16%'>项目介绍：</td>
	<td class="project-content">本项目是基于上海市社区矫正总和管理平台为浙江省全新制作的社区矫正综
合管理平台</td>
</tr>
<tr>
	<td class="project-item">涉及技术：</td>
	<td class="project-content">SpringBoot+Jpa+Activiti+Kettle</td>
</tr>
<tr>
	<td class="project-item">职责描述：</td>
	<td class="project-content">了解了平台切换的大体流程， 对双向数据同步、 跨域请求等有了更深 入的理
解，并且逐步自己设计部分技术框架的功能，对如何更好的开发、更有效率
的开发有了更深入的理解。使用基于 shardingJdbc 的 mysql 读写分离、分表功能。
</td>
</tr>
</table><br/><br/><br/>