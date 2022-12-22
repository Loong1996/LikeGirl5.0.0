# Like_Girl V5.0.0


- 演示地址：[演示](https://love.kikiw.cn)
- 项目文档地址：[查看文档](https://blog.kikiw.cn/index.php/archives/46/)
  ![首页](https://img.gejiba.com/images/d1947b697e6735637a6e460332ba14cd.png)
  ![后端](https://img.gejiba.com/images/7f71be28f996a744fdfacc9f663ec975.png)

### 前言

* 本项目完全免费 有能力的朋友可以进行二次开发
* 但禁止以任何方式出售
* 初衷就是学习交流 如果可以哄你对象开心 那也是一个不错的选择
#### 项目声明

* 本项目也许就到此为止了 我也没有再多的时间去维护
* 2022年最后一个版本 也是项目的最后一个版本 今天刚好是冬至 节日快乐～
* 但是在这里还是得再次强调 项目完全免费 禁止倒卖 以任何方式出售
* 以前有在卖的也就算了我也不再去计较 希望之后别让我再看到～
* 写这个的初衷就是为了学习 我也没想过要收费什么的
* 但是在这里还是得再次强调 项目完全免费 禁止倒卖 以任何方式出售
* 如果有人脸皮这么厚 拿开源的项目去卖钱 那你真是活不起了 我可以理解
* 开发不易也需要许多精力和时间 请尊重作者版权
* 前端页面版权信息可以进行删除（前端底部）...
* 目前写入了Pjax无限加载 页面体验会更加高效 音乐不会打断播放 一切正常使用 调试了两天基本遇到的问题都已经解决
* 后端使用了Ajax异步请求提交数据 配合插件提醒弹窗
* 最后强调 项目完全免费 尊重作者版权 请带有版权意识 感谢～

##   江湖路漫漫 我们有缘再见

#### LikeGirl5.0.0更新说明

* 写在前面 修改版权的我建议你别用 不尊重别人的成果非常可耻
* 新增前端全站pjax无限加载技术
* 新增前后端Ajax数据异步请求技术
* 新增前端头部头像背景高斯模糊开关
* 新增前端Pjax无限加载开关
* 新增修改敏感信息需输入安全码操作
* 新增自定义前端全局CSS样式
* 新增自定义前端头部全局内容（可添加css外链或其他内容）
* 新增自定义前端底部全局内容（可添加js外链或其他内容）
* 优化后端留言页内容/数量显示过长问题
* 优化后端数据编码 进行html字符转义
* 优化部分页面数据库预处理内容
* 优化前端部分页面加载动画效果
* 优化提醒弹窗 使用开源插件 美观主要
* 优化前端留言板部分CSS样式 数据获取判断
* 修复在数据库内容虚拟主机/空间中文内容显示“???”
* 修复后台管理登录页对密码判断特殊字符问题
* 修复网站备案号点击无法跳转工信部官网
* 再次声明 我写这个项目只是练练手完全没有考虑过挣一分钱 禁止以任何方式出售 一切后果自行负责

#### LikeGirl4.0.0更新说明

* 新增相册页 可在后台填写相关信息进行新增或修改删除
* 新增前端部分页面动画 可在后台打开或关闭 默认为开
* 优化留言页时间显示格式 改为显示xx分钟前 xx天前
* 优化留言游客IP地区显示 IP无法获取到地址的显示为未知
* 增强留言页数据过滤 特殊字符一切过滤为空
* 优化恋爱列表页列表图片判断显示图片小图标
* 本次更新以安全性为主 其他无太大改动 建议所有用户更新
* 4.0以下版本遇到的bug我已统一收集修复  用户可在后台`关于Like Girl` 模块查看最新版本等公告信息



#### LikeGirl3.5更新说明

* 新增留言页输入QQ ajax异步请求获取QQ昵称 无需手动填写
* 新增IP拉黑管理 管理员可以添加需拉黑的IP或删除
* 新增非法请求列表页面 管理员可在后台查看非法请求的 路径 IP等数据
* 新增留言页设置 管理员可设置前端显示的留言数量 违禁词拦截
* 新增公告页面 如有bug或更新项目会在页面内显示提醒
* 新增IP拉黑提醒页面 提醒被拉黑原因
* 新增非法访问提醒页面 记录非法访问用户的IP 时间 当前路径
* 修复新增事件页面数据判断 第一次填写图片不显示的bug
* 修复基本设置模块 不填写密码会更新密码bug
* 修复基本设置模块 更换用户名后前端页面访问直接跳转登录页面bug
* 修复点点滴滴页面需添加初始化标签的问题 之后可以直接书写HTML标签 正常渲染
* 增强留言页留言内容检测 防止xss漏洞注入 对昵称和内容进行过滤
* 增强留言页数据接收 防止注入空内容等问题
* 增强所有表单数据接收处理页面的判断
* 优化顶部栏文字颜色 判断页面距离更改CSS 字体颜色 过渡动画
* 优化数据库连接失败页面提醒
* 优化留言页部分样式

### 更新说明

- 更换后台模板 所有页面
- 后台新增相关信息配置 可设置管理员QQ Name
- 后台首页重写 数据查看一目了然
- 后台基本设置模块优化 起始时间选择优化
- 后台留言管理页面新增留言者IP记录IP归属地显示（只显示省份）
- 后台点点滴滴管理页面新增文章筛选功能
- 后台点点滴滴页面新增/修改文章内容引入编辑器插件
- 后台恋爱清单管理页面新增查看事件缩略图功能
- 后台恋爱清单新增/修改事件内容优化已完成与未完成按钮显示图片地址输入框功能
- 前端页面新增情侣头像中间爱心动画
- 前端点点滴滴页面引入图片灯箱插件 md语法解析插件
- 前端留言板页面样式优化 新增留言者IP归属地显示（显示省份）
- 前端关于我们页面引入机器人对话插件
- 增强留言板留言内容 正则表达式对含有特殊字符的内容进行判断过滤（防止xss漏洞注入）
- 修复文章发布时无法填写发布者Name

#### 使用说明

- 文章书写需了解HTML标签基本语法
- 可以百度查询资料学习
- 部署后会有一篇默认文章 可以参考书写格式

#### 食用方法
1.打开根目录下的`admin`文件夹
2.接着找到`Config_DB.php`文件打开编辑你的数据库相关信息
3.请认真填写安全码 尽量设置的`复杂难以猜测` 修改密码等敏感信息需输入安全码
4.最后到数据库导入sql文件（`like_girl.sql`）
5.默认账号密码：`admin`/`love`
#### 留言反馈


- 花有重开日 人无再少年
- 一辈子很短 要爱对的人
- 珍惜眼前人 欢迎使用Like_Girl V5.0.0（最终版）
- 使用过程中如遇到bug或建议请反馈到邮箱
- mail@kikiw.cn

