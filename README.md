# Typecho主题 - Initial 简约而不简单（v2.5）

![主题封面](https://www.offodd.com/usr/uploads/2018/09/111355748.png)

主题命名为**Initial**，意为“**初**”，专注于文字，算是极极极简风格吧，简约而不简单，希望你能喜欢这种很小众的风格。

主题预览：[https://www.offodd.com/](https://www.offodd.com/)

## 功能与特点

* 重新优化的响应式布局，移动端舒适体验
* 轻量级设计，关闭附加功能后无框架、无JQ、无库
* 傻瓜式后台设置，告别使用疑惑
* 公共资源支持切换源：Staticfile、jsDelivr、CDNJS
* Gravatar头像支持切换源：官方源、国内源、V2EX源。
* 支持CSS文件、文章附件自定义链接，实现CDN加速
* 全站Pjax、Ajax评论、Ajax翻页、HTML压缩、CSS文件压缩
* 支持自定义Favicon图标，自定义头部跟随或固定，自定义标题或LOGO，自定义导航栏显示内容
* 支持自定义文章缩略图或者获取文章内任意图片作为缩略图
* 支持面包屑导航、文章目录、文章二维码打赏
* 支持“轻语”功能（类似说说）
* 自带链接功能，可在首页（侧栏或页底）和链接模板内显示，可自定义要显示的分类
* 添加侧边栏轻语、热门文章、标签云
* 添加三套极简模板：轻语模板、归档模板和链接模板
* 支持自定义备案号、自定义网站统计代码
* 添加右下角小工具，包括返回顶部、背景音乐
* 更多细节，等你发现🤩

## 使用与更新

### 下载与使用

进入[下载页面](https://www.offodd.com/17.html)，下载主题包并解压（若是从GitHub下载，建议把解压出来的文件夹改名为“initial”），将文件夹上传至网站文件主题目录下，网站后台启用主题即可。

主题设置方面的问题可以看[这里](https://www.offodd.com/58.html)

### 更新

更新版本时，下载新版主题包并解压，直接把解压后的文件覆盖上传即可（对主题有修改请自行备份），无需切换至其他主题（这样就不会丢失设置）。

如发现BUG等问题，也请随时[站内反馈](https://www.offodd.com/17.html#comments)😋

## 更新历史

2018/9/4：发布第一版
<br>2018/9/8：更新1.1版本
<br>2018/9/12：更新1.2版本
<br>2018/9/17：更新1.2.1版本（增加返回顶部过渡动画，微调部分样式，添加标签云，修复小BUG）
<br>2018/9/28：更新1.3版本
<br>2018/10/12：更新2.0版本
<br>2018/11/2：更新2.1版本
<br>2018/11/23:更新2.2版本
<br>2018/11/28:更新2.2.1版本
<br>2018/12/14:更新2.3版本
<br>2018/12/24:更新2.3.1版本
<br>2018/12/25:更新2.3.2版本
<br>2019/1/4:更新2.4版本
<br>2019/1/9:更新2.4.1版本
<br>2019/1/14:更新2.4.2版本
<br>2019/2/20:更新2.4.3版本
<br>2019/12/11:更新2.4.4版本
<br>2020/9/4:更新2.4.5版本
<br>2020/9/11:更新2.5版本

**2.5版更新内容**

> * js写入独立文件
> * 修复关闭Ajax翻页时,加密文章无法打开的问题
> * 删除公共静态资源来源“BootCDN”（太不稳定）
> * 其他微调优化

本次更新主要是把js语句全部写入独立的js文件，配合pjax和cdn，访问速度理论上应该有所提升，其余更新内容不多。

**2.4.5版更新内容**

> * 站点标题支持自定义显示方式（仅文字、仅LOGO、LOGO+文字）
> * 文章目录添加全局开关
> * 添加Staticfile静态资源CDN
> * 其他微调

更新内容不多，不想覆盖升级的可以参照GitHub自行修改。

**2.4.4版更新内容**

> * 优化分类名过长时的显示问题
> * 备案号链接地址更新
> * archive页面添加文章阅读量显示
> * 关闭偶尔可能会出现的无关紧要的php提示
> * 其他优化与小调整

小小更新一下，以上问题基本不影响使用，想省事的可以自行修复一下即可。

**2.4.3版更新内容**

> * 删除外观设置内从2.4版本开始弃用的链接列表（已迁移至 管理-独立页面-链接模板页面-自定义字段-links 内）
> * 新增“轻语”的评论回复功能，并优化评论样式
> * 新增文章底部“文章许可信息”，可在后台自定义内容
> * 修复“轻语”评论无法换行的问题
> * 修复某些情况下“文章目录”按钮状态异常
> * 修复“注脚”链接新窗口打开的问题
> * 优化导航下拉列表，不再限制宽度
> * 优化评论框架结构，回复评论目标更清晰
> * 其他优化与小调整

**注意**：从本版开始，后台-外观设置内的 链接列表 已彻底删除，新的链接列表已迁移至 管理-独立页面-链接模板页面-自定义字段-links 内，以后的链接操作都需要在这里进行。

**2.4.2版更新内容**

> * 新增背景音乐“随机播放”选项，请在 后台-控制台-外观-设置外观-背景音乐 处修改
> * 将文章、页面、轻语的外链接、评论者的链接修改为使用使用新窗口打开（仅外链接使用新窗口，本站链接还在当前页打开）
> * 调整“文章目录”按钮位置到右下角并美化界面，仅当文章有目录时，才会显示
> * 后台设置选项判断优化（老用户请进入 后台-设置外观 将未选择的设置项重选一下即可，不影响使用，请正常升级）
> * 其他优化与小调整

本次更新以查找问题为主，需要注意的就是主题设置项进行了优化，新用户忽略即可，老用户升级后，请到 后台-设置外观 ，可以看到有几个单选的设置项被清空了，只需要重新选择一下并保存就行，当然，如果你不重新选择，也不会影响使用🤨。

**2.4.1版更新内容**

> * 调整“文章目录”选项位置到 编辑文章 内，可单独设置每篇文章是否显示文章目录（默认关闭）
> * 调整侧边栏“最近回复”超链接，点击自动跳转至评论位置
> * 部分代码优化

本次更新依然是小更新，优化为主，主要是调整了“文章目录”的开启关闭方式，从之前的 主题设置 移动到 编辑文章 内，可单独设置每篇文章是否显示文章目录（默认关闭）。

**2.4版更新内容**

> * 新增文章阅读量统计与显示
> * 新增文章目录（默认关闭）
> * 新增“轻语”的评论功能
> * 将“链接列表”迁移至“链接”页面内，防止丢失
> * 稍微增加移动端字体大小
> * 修复关闭Pjax时某些情况下无法评论
> * 修复几处PHP Notice
> * 优化Archive作者页标题
> * 优化热门文章排序规则
> * 代码优化和其他优化调整

**注意：从2.4版开始，链接列表 已迁移至 管理-独立页面-链接模板页面-自定义字段-links 内，以后的链接操作都需要在这里进行，主题设置处的列表暂留备份，再更新几次后将会彻底删除。**

此次更新最需要注意的就是“链接列表”，从主题设置迁移到了“链接”模板页面的自定义字段内。

老用户更新2.4版主题后

若已创建 **链接模板页面**，前台刷新该页面，将会自动将之前的 **链接列表** 迁移至 **链接模板页面** 内。

若未创建 **链接模板页面**，请前往 **管理-独立页面-新增页面-自定义模板-选择“链接”** 创建“链接”模板页面，然后前台访问该页面，将会自动将之前的 **链接列表** 迁移至 **链接模板页面** 内。

新用户若需要使用“链接”功能，请前往 **管理-独立页面-新增页面-自定义模板-选择“链接”** 创建“链接”模板页面，然后新增“自定义字段”，字段名称设置为`links`，字段值按照之前的 **链接格式** 输入即可。具体使用方法可以[点击这里](https://www.offodd.com/58.html)查看。

**2.3.2版更新内容**

> * 优化子分类显示（同一父分类下的所有级别的子分类都将显示在该父分类下，级别太多也不好吧😥）。
> * 其他小调整。

子分类这个东西之前从来没有使用过，所以也一直没有发现这个问题，谢谢网友**@luvnaxx**发现并提出。

**2.3.1版更新内容**

> * 新增切换Gravatar头像源，官方源、国内源、V2EX源
> * 丰富Ajax翻页选项，自动、点击、关闭
> * **删除DNS预获取、删除自定义Apple图标**
> * 其他优化与小调整

最近年底了，事情很多，更新不会很大，以优化和修复为主。

**2.3版更新内容**

> * 新增Ajax翻页，支持自动翻页与点击翻页
> * 新增“轻语”功能（类似说说），并新增一套极简“轻语”模板，支持在首页和侧边栏显示
> * 文章缩略图支持调用文章内的任意图片（例如：输入数字“2”代表使用文章内第二张图片）
> * 再次优化加密文章与Pjax冲突问题，已经趋近完美
> * 解决进入“归档”页面时侧边栏的文章数量异常
> * 其他功能优化与小调整（比较多，记不清了）

本版更新主要在“轻语”这个功能，折腾了很久，本以为挺简单，但实际操作才发现有很多小问题，还好都解决了，目前正常使用没问题，后续更新会丰富此功能。
其次就是添加了Ajax翻页，这个也是很多朋友期待的，欢迎更新品尝，若有问题随时站内反馈😋

**2.2.1版更新内容**

> * 链接功能添加链接图标参数
> * 链接模板内的链接增加图标显示（默认关闭）
> * 其他小调整

本版更新为小更新，主要由于在后台的“链接列表”增加了一个“链接图标”的参数，考虑到要尽量减少对使用者的影响，故提前更新。

**2.2版更新内容**

> * 添加侧边栏动态滚动（默认关闭）
> * 调整右下角小工具位置，解决超宽屏尴尬
> * 添加背景音乐播放进度条
> * 修复关于链接的小问题
> * 清除翻译语句
> * 其他细节调整与小BUG修复

**2.1版更新内容**

> * 新增一套链接模板
> * 新增链接功能，可在首页（侧栏或页底）和链接模板内显示，可自定义要显示的分类
> * 新增自定义公共静态资源来源，支持BootCDN、CDNJS、jsDelivr
> * 修复加密文章与Pjax有冲突的问题（感谢okgo发现并提出此BUG，估计带Pjax的TE主题都有此问题😖）
> * 修复侧边栏热门文章显示数量使其与后台设置一致
> * 移除Normalize，将其优化集成进主题css
> * 背景音乐优化、界面微调优化
> * 其他细节调整与小BUG修复（优化了很多细节，记不起来了🤣）

**2.0版更新内容**

> * 公共静态资源由BootCDN替换为CDNJS（BootCDN已暂停）
> * 重新设计的网站头部样式
> * 新增可将头部设置为固定显示
> * 新增导航栏可自定义显示分类、页面、是否合并显示等（充足的自定义）
> * 新增自定义副标题，取消自定义描述（因为头部重做后已不显示此项）
> * 新的a标签颜色，整体样式微调
> * 新增面包屑导航（可自定义）
> * 新增侧边栏热门文章
> * 其他细节调整与小BUG修复

本版更新主要在外观，变化较大，当然，细节和新增功能也是精益求精，望君喜。

**1.3版更新内容**

> * 使用excerpt摘要函数，可自动截取摘要
> * ~~阅读量统计（这个目前还不确定是否要加上）~~*暂时不加*
> * 自定义文章缩略图或者自动调用文章第一张图片作为缩略图
> * URL替换（主要是方便于使用七牛等cdn的静态文件镜像加速）
> * HTML代码压缩
> * 背景音乐添加支持多首歌曲循环，添加错误歌曲检测，自动跳过
> * 添加评论区文章作者小标签
> * 其他细节调整与优化

**1.2版更新内容**

> * 优化部分细节
> * 修复一处关于Ajax评论的逻辑性小错误
> * 添加右下角小工具
>  * 返回顶部(1.2.1版添加过渡动画)
>  * 背景音乐
> * 侧边栏添加标签云（1.2.1）

背景音乐这个真是折腾了好久，因为主要是想使用网易的音乐，再加上要尽量做到最轻量，看了几个API框架，直接就放弃了（虽然做完只有不到100KB，但还是觉得太大了），最后找到一个不错的开放API，可惜不支持https😖貌似没办法了。。。
<br>晚上回家思考了一下，制作本主题的初衷就是简约而不简单，既然是要“简约”何不做到极致？好像找到了新的大门🤩

最后确定使用原生HTML5播放器（隐藏式），后台自定义**一首**你最最喜欢的音乐循环播放（后台可给音乐设置一个合适的音量），仅使用一个按钮来集成**显示播放状态**、**播放控制**、~~懒加载~~（由于部分移动端浏览器的特殊内置设置问题，此项已经取消；其实通过监听触控可以解决，但是还是算了吧，不过放心，仍然不会影响我们宝贵的页面加载速度。）*显示播放和暂停状态由纯CSS实现；播放和暂停控制由原生JS实现。*虽然没有使用框架那么强大的功能和兼容性，但觉得非常符合本主题初衷。

**1.1版更新内容**

> * 全站Pjax + ajax评论
> * 二维码打赏
