# less-os

简介：<br />
less-os是一个简单实用的less库，由作者从日常项目中积累整理而来，包含了浏览器兼容前缀补全和IE8等低版本浏览器兼容，适用于移动端和PC端开发.

<br /><br />
文件说明：<br />
less_os.less   -less库主文件，存放公共属性和方法<br />
init.less  -less源码，存放项目less源码

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
		<td>.border-radius()</td>
		<td>设置圆角</td>
		<td>可设参数<br /> 参数1：@radius - 圆角值</td>
	</tr>
	<tr>
		<td>.border-cus-radius()</td>
		<td>自定义圆角</td>
		<td>可设参数<br /> 参数1：@radiusTop - 顶部圆角<br /> 参数2：@radiusRight - 右侧圆角<br />参数3：@radiusBottom - 底部圆角<br />  参数4：@radiusLeft - 左侧圆角</td>
	</tr>
	<tr>
		<td>.border-tl-radius()</td>
		<td>设置左上角圆角</td>
		<td>可设参数<br /> 参数1：@radius - 圆角值</td>
	</tr>
	<tr>
		<td>.border-tr-radius()</td>
		<td>设置右上角圆角</td>
		<td>可设参数<br /> 参数1：@radius - 圆角值</td>
	</tr>
	<tr>
		<td>.border-bl-radius()</td>
		<td>设置左下角圆角</td>
		<td>可设参数<br /> 参数1：@radius - 圆角值</td>
	</tr>
	<tr>
		<td>.border-br-radius()</td>
		<td>设置右下角圆角</td>
		<td>可设参数<br /> 参数1：@radius - 圆角值</td>
	</tr>
	<tr>
		<td>.border-image()</td>
		<td>设置边框图片</td>
		<td>可设参数<br /> 参数1：@url - 图片路径<br /> 参数2：@width - 宽度<br />参数3：@repeat - 循环模式</td>
	</tr>
	<tr>
		<td>.no-box-shadow()</td>
		<td>去除阴影</td>
		<td></td>
	</tr>
	<tr>
		<td>.box-shadow()</td>
		<td>设置阴影</td>
		<td>可设参数<br /> 参数1：@x - x轴偏移<br /> 参数2：@y - y轴偏移<br />参数3：@blur - 模糊距离<br /> 参数4：@color - 阴影颜色</td>
	</tr>
	<tr>
		<td>.no-text-shadow()</td>
		<td>去除文本阴影</td>
		<td></td>
	</tr>
	<tr>
		<td>.text-shadow()</td>
		<td>设置文本阴影</td>
		<td>可设参数<br /> 参数1：@x - x轴偏移<br /> 参数2：@y - y轴偏移<br />参数3：@blur - 模糊距离<br /> 参数4：@color - 阴影颜色</td>
	</tr>
	<tr>
		<td>.text-overflow()</td>
		<td>设置单行文本截取</td>
		<td></td>
	</tr>
	<tr>
		<td>.text-xline()</td>
		<td>设置多行文本截取</td>
		<td>可设参数：<br /> 参数1：@line - 截取行数<br /> 注：该方法只支持chrome内核浏览器</td>
	</tr>
	<tr>
		<td>.pos-rel()</td>
		<td>设置相对定位</td>
		<td></td>
	</tr>
	<tr>
		<td>.pos-abs()</td>
		<td>设置绝对定位</td>
		<td></td>
	</tr>
	<tr>
		<td>.pos-fix()</td>
		<td>设置窗口定位</td>
		<td></td>
	</tr>
	<tr>
		<td>.pos-center()</td>
		<td>设置定位居中(margin-left),适合有固定宽度</td>
		<td>可设参数<br /> 参数1：@width - 盒子宽度<br /> 参数2：@height - 盒子高度<br />参数3：@position - 定位方式</td>
	</tr>
	<tr>
		<td>.pos-center-trans()</td>
		<td>设置定位居中(translate)，适合没有固定宽度且不需要支持IE8以下浏览器</td>
		<td>可设参数<br /> 参数1：@position - 定位方式</td>
	</tr><tr>
		<td>.opacity()</td>
		<td>设置透明度</td>
		<td>可设参数：<br /> 参数1：@opacity - 透明度（可选值：0 ~ 100）</td>
	</tr>
	<tr>
		<td>.background-image()</td>
		<td>设置背景图</td>
		<td>可设参数<br /> 参数1：@image - 图片路径<br /> 参数2：@position - 图片定位<br />参数3：@repeat - 循环方式<br />参数4：@size - 背景图覆盖大小</td>
	</tr><tr>
		<td>.background-size()</td>
		<td>背景尺寸</td>
		<td>可设参数：<br /> 参数1：@size - 尺寸（默认值：auto）</td>
	</tr>
	<tr>
		<td>.background-clip()</td>
		<td>背景覆盖的位置</td>
		<td>可设参数：<br /> 参数1：@background-clip - 背景覆盖的位置（默认值：border-box）</td>
	</tr>
	<tr>
		<td>.background-origin()</td>
		<td>背景开始的位置</td>
		<td>可设参数：<br /> 参数1：@background-origin - 背景开始的位置（默认值：padding-box）</td>
	</tr>
	<tr>
		<td>.background-rgba()</td>
		<td>设置透明背景色</td>
		<td>可设参数<br /> 参数1：@red - 红色通道色值<br /> 参数2：@green - 绿色通道色值<br />参数3：@blue - 蓝色通道色值<br />参数4：@alpha - 透明度</td>
	</tr>
	<tr>
		<td>.mask()</td>
		<td>设置遮罩</td>
		<td>可设参数<br /> 参数1：@url - 遮罩图片路径<br /> 参数2：@position - 遮罩开始位置<br />参数3：@repeat - 循环方式<br />参数4：@size - 遮罩尺寸<br />参数5：@clip - 设置裁切方式</td>
	</tr>
	<tr>
		<td>.mask-image()</td>
		<td>设置遮罩图片</td>
		<td>可设参数<br /> 参数1：@url - 遮罩图片路径</td>
	</tr>
	<tr>
		<td>.mask-mode()</td>
		<td></td>
		<td>根据资源的类型自动采用合适的遮罩模式,目前仅Firefox浏览器支持,可以支持同事设置多个值,默认值是match-source</td>
	</tr>
	<tr>
		<td>.mask-position()</td>
		<td>设置图形位置</td>
		<td>可设参数<br /> 参数1：@type - 设置图形位置</td>
	</tr>
	<tr>
		<td>.mask-repeat()</td>
		<td>设置图形填充</td>
		<td>可设参数<br /> 参数1：@type - 设置图形填充（默认值：repeat）</td>
	</tr>
	<tr>
		<td>.mask-clip()</td>
		<td>设置裁切</td>
		<td>可设参数<br /> 参数1：@type - 设置裁切（默认值：no-clip）</td>
	</tr>
	<tr>
		<td>.mask-origin()</td>
		<td>背景开始的位置</td>
		<td>可设参数<br /> 参数1：@type - 背景开始的位置</td>
	</tr>
	<tr>
		<td>.mask-size()</td>
		<td>设置遮罩图片尺寸</td>
		<td>可设参数<br /> 参数1：@type - 设置遮罩图尺寸（默认值：auto）</td>
	</tr>
	<tr>
		<td>.mask-typ()</td>
		<td>设置不同的遮罩模式</td>
		<td>可设参数<br /> 参数1：@type - 设置不同的遮罩模式（默认值：luminance）</td>
	</tr>
	<tr>
		<td>.mask-composite()</td>
		<td>表示当同时使用多个图片进行遮罩时候的混合方式</td>
		<td>可设参数<br /> 参数1：@type，支持属性: [ add | subtract | intersect | exclude ]</td>
	</tr>
	<tr>
		<td>.no-mask()</td>
		<td>去除遮罩</td>
		<td></td>
	</tr>
	<tr>
		<td>.triangle()</td>
		<td>使用css设置三角形</td>
		<td>可设参数<br /> 参数1：top | right | bottom | left - 表示三角形朝向<br /> 参数2：width - 宽度<br /> 参数2：color - 三角形颜色</td>
	</tr>
	<tr>
		<td>.content-columns()</td>
		<td>分列布局</td>
		<td>可设参数<br /> 参数1：@columnCount - 设置列数<br /> 参数2：@columnGap - 指定列之间的间距<br />参数3：@rule-width - 指定列之间的规则：宽度，样式和颜色<br />参数4：@rule-style - 指定列之间的样式<br />参数5：@rule-color - 指定列之间的颜色</td>
	</tr>
	<tr>
		<td>.no-transform()</td>
		<td>清除transform</td>
		<td></td>
	</tr>
	<tr>
		<td>.rotate()</td>
		<td>设置旋转角度</td>
		<td>可设参数<br /> 参数1：@degrees - 设置旋转角度</td>
	</tr>
	<tr>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</table>
