# less-os

简介：<br />
less-os是一个简单实用的less库，由作者从日常项目中积累整理而来，包含了浏览器兼容前缀补全和IE8等低版本浏览器兼容，适用于移动端和PC端开发.

<br /><br />
文件说明：<br />
less_os.less   -less库主文件，存放公共属性和方法<br />
whir_css.less  -less源码，存放项目less源码

<br /><br />
方法列表：<br />

<table width="100%">
	<tr>
		<th>方法</th>
		<th>作用</th>
		<th>参数说明</th>
	</tr>
	<tr>
		<td>.clear-mp()</td>
		<td>清除margin和padding</td>
		<td></td>
	</tr>
	<tr>
		<td>.box-sizing()</td>
		<td>box-sizing 盒模型计算方式</td>
		<td>
			可设参数 <br /> 参数1：@boxmodel - 盒子模式<br />默认值： content-box <br />
			可选值：<br /> content-box | padding-box | border-box
		</td>
	</tr>
	<tr>
		<td>.display-flex()</td>
		<td>设置弹性盒子</td>
		<td>无参数</td>
	</tr>
	<tr>
		<td>.font-face()</td>
		<td>自定义字体</td>
		<td>
			可设参数<br />
			参数1：@path - 文字存放路径 <br /> 默认值：'../fonts' <br /> 参数2：@font-name - 字体名称<br /> 无默认值
		</td>
	</tr>
	<tr>
		<td>.writing-mode()</td>
		<td>文本在水平或垂直方向上如何排布</td>
		<td>可设参数<br /> 参数1：@mode - 模式<br /> horizontal-tb | vertical-rl | vertical-lr | sideways-rl | sideways-lr</td>
	</tr>
	<tr>
		<td>.calc()</td>
		<td>计算器</td>
		<td>可设参数<br /> 参数1：@mode - 宽度/高度<br /> 可选参数：width | height </td>
	</tr>
	<tr>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td></td>
		<td></td>
	</tr>
	<tr>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>
