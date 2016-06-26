# Html5部分标签整理
|标签        | 说明           | 示例  |
| :-------------: |:-------------:| :-----|
|&lt;!DOCTYPE&gt;|用来定义Html版本|&lt;!DOCTYPE&gt;|
|&lt;html&gt;| 用来表示整个页面的开始和结束 | &lt;html&gt;<br />......<br/>&lt;/html&gt; |
|&lt;head&gt;|用来表示页面中包含页面数据的特殊部分，包括其标题以及对外部资源的引用。这个元素的内容不直接输出到屏幕上，但会影响页面的美观和行为，这个元素放在&lt;html&gt;中。|&lt;head&gt;<br/>......<br/>&lt;/head&gt;|
|&lt;title&gt;|用来定义页面的标题。这个 标题将会显示在浏览器的标题栏中。这个元素放在&lt;head&gt;中|&lt;title&gt;欢迎来到我的第一个站点&lt;/title&gt;|
|&lt;body&gt;|用来表示页面正文的开始和结束。其内容就是在浏览器中显示的内容。这个元素放在&lt;html&gt;元素中|&lt;body&gt;<br/>这里是内容<br/>&lt;/body&gt;|
|&lt;header&gt;|用来表示页面的标题部分。这个元素和这个表中的所有剩余元素都放在&lt;body&gt;元素中|&lt;header&gt;<br/>&lt;img src="example.png"/&gt;<br/>&lt;/header&gt;|
|&lt;main&gt;|用来表示页面的核心内容|&lt;main&gt;......&lt;/main&gt;|
|&lt;section&gt;|用来表示页面中的各个部分。每个页面中可以有很多部分|&lt;section&gt;......&lt;/section&gt;|
|&lt;aside&gt;|用来表示不属于核心页面的内容，这些内容显示为侧栏|&lt;aside&gt;<br/>&lt;img src="example.png"/&gt;<br/>&lt;/aside&gt;|
|&lt;article&gt;|用来表示页面中的主要内容|&lt;article&gt;主页面&lt;/article&gt;|
|&lt;footer&gt;|用来表示页面的页脚部分|&lt;footer&gt;页脚&lt;/footer&gt;|
|&lt;a&gt;|用来将一个Web页面链接到另一个页面，或者创建 页面中的链接|&lt;a href="http://www.example.com"&gt;一个示例站点&lt;/a&gt;|
|&lt;img&gt;|用来向页面中嵌入图像|&lt;img src="examplr.png" /&gt;|
|&lt;strong&gt;<br/>&lt;em&gt;|用来将文本格式格式化为粗体或斜体|这是一个&lt;strong&gt;<strong>粗体</strong>&lt;/strong&gt;<br/>这是一个&lt;em&gt;<em>斜体</em>&lt;/em&gt;|
|&lt;form&gt;<br/>&lt;input&gt;<br/>&lt;textarea&gt;<br/>&lt;select&gt;<br/>&lt;option&gt;|用于描述允许用户向服务器提交信息的输入格式<br/>&lt;input&gt;中type分别有以下属性可供选择:<br/>hidden,text,search,tel,url,<br/>email,password,date,time,number,<br/>range,color,checkbox,radio,file,<br/>submit,image,reset,button|&lt;form action="example.html" method="post"&gt;<br/>&lt;input type="text"/&gt;<br/>&lt;select&gt;<br/>&lt;option&gt;example&lt;/option&gt;<br/>&lt;/select&gt;<br/>&lt;/form&gt;|
|&lt;table&gt;<br/>&lt;caption&gt;<br/>&lt;thead&gt;<br/>&lt;tbody&gt;<br/>&lt;tfoot&gt;<br/>&lt;tr&gt;<br/>&lt;th&gt;<br/>&lt;td&gt;|这些标记用来创建带表格的布局。<br/>&lt;table&gt;标记定义整个表格，<br/>&lt;caption&gt;用于表示表格标题<br/>&lt;thead&gt;用于标记表格头部，<br/>&lt;tbody&gt;用于标记表格主题内容，<br/>&lt;tfoot&gt;用于标记表格脚部，<br/>&lt;th&gt;用于表示标题单元格，<br/>而&lt;tr&gt;与&lt;td&gt;标记分别用来定义行和单元格|&lt;table&gt;<br/>&lt;caption&gt;example table&lt;caption/&gt;<br/>&lt;thead&gt;<br/>&lt;th&gt;example1&lt;/th&gt;<br/>&lt;th&gt;example2&lt;/th&gt;<br/>&lt;/thead&gt;<br/>&lt;tbody&gt;<br/>&lt;tr&gt;<br/>&lt;td&gt;a1&lt;/td&gt;<br/>&lt;td&gt;b1&lt;/td&gt;<br/>&lt;/tr&gt;<br/>&lt;tr&gt;<br/>&lt;td&gt;a2&lt;/td&gt;<br/>&lt;td&gt;b3&lt;/td&gt;<br/>&lt;/tr&gt;<br/>&lt;/tbody&gt;<br/>&lt;tfoot&gt;<br/>&lt;th&gt;example1&lt;/th&gt;<br/>&lt;th&gt;example2&lt;/th&gt;<br/>&lt;/tfoot&gt;<br/>&lt;/table&gt;|
|&lt;ul&gt;<br/>&lt;ol&gt;<br/>&lt;li&gt;|这三个标记用来创建带编号或者项目符号的列表。&lt;ul&gt;和&lt;ol&gt;标记定义列表的外观（要么是无序的，带一个简单的项目符号；要么是有序的，带有编号），而&lt;li&gt;标记用来显示列表中的项|&lt;ul&gt;&lt;li&gt;example1&lt;/li&gt;&lt;li&gt;example2&lt;/li&gt;&lt;/ul&gt;<br/>&lt;ol&gt;&lt;li&gt;example3&lt;/li&gt;&lt;li&gt;example4&lt;/li&gt;&lt;/ol&gt;|
|&lt;span&gt;|这个标记用来包装盒影响文档的其他部分。它显示为内联文本，所以不会向页面添加换行符|&lt;span&gt;example text &lt;/span&gt;|
|&lt;div&gt;|与&lt;span&gt;标记一样，&lt;div&gt;标记用来作为其它元素的容器。然而，&lt;div&gt;标记是块级元素，默认情况下它会使&lt;div&gt;元素的前后出现显式的换行符|&lt;div&gt;example text&lt;/div&gt;|
|&lt;audio&gt;<br/>&lt;video&gt;<br/>&lt;source&gt;|用于在Web页面中嵌入音频和视频文件。&lt;source&gt;元素用于定义多种类型的音频和视频资源|&lt;video src="video.avi" /&gt;|

更多关于Html5的标签信息请访问 [W3C](https://www.w3.org/TR/html5/index.html)