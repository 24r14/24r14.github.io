# Zhuodan Yin — Personal website

大学申请与个人介绍网站第一版。纯 HTML / CSS / 少量 JavaScript，无需安装依赖、无需构建，可直接打开 index.html。

## 部署到 GitHub Pages

网站仓库：**[24r14/24r14.github.io](https://github.com/24r14/24r14.github.io)**。发布地址为 https://24r14.github.io/ ，实际部署结果请以仓库 Settings → Pages 的状态为准。

1. 使用已创建的公开仓库 24r14/24r14.github.io。
2. 将本文件同级的所有文件上传到仓库根目录，保留 assets 文件夹。不要把外层 24r14.github.io 文件夹作为额外一层上传。
3. 打开仓库 Settings → Pages，Source 选 Deploy from a branch，分支 main，目录 / (root)，点击 Save。
4. 等待 GitHub 的 Pages 部署成功，然后在 Pages 设置页点击 Visit site。预期地址为 https://24r14.github.io/ 。
5. 后续修改相应 HTML 或 CSS 并提交到 main，Pages 会重新发布。

官方说明：[创建 Pages 网站](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)、[配置发布来源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。

本项目不需要 Actions 工作流、密钥、后台或付费服务。.nojekyll 用于直接发布静态文件。也可部署在普通项目仓库，所有导航和资源均使用相对路径。

## 修改哪里

| 内容 | 文件 |
|---|---|
| 首页介绍、精选项目 | index.html |
| 自我介绍 | about.html |
| 研究兴趣 | research.html |
| 项目记录、成果与外链 | projects.html |
| 思考方式 | how-i-think.html |
| 学习方法与笔记 | learning.html |
| 简历概览，浏览器打印/PDF | resume.html |
| 颜色、字体、间距、响应式和打印样式 | assets/styles.css |
| 手机导航、打印按钮 | assets/site.js |

每页都是完整 HTML，关闭 JavaScript 仍可阅读和导航。共享页眉、导航和页脚有意直接放在各页中：修改导航时需同步全部页面。主色在 CSS 顶部变量中调整。没有外部字体、分析追踪、联系表单或第三方运行库。

## 本地预览

直接双击 index.html 即可。也可以在本目录运行已有 Python 的 python -m http.server 4173 --bind 127.0.0.1，再访问 http://127.0.0.1:4173 。使用结束后 Ctrl+C 停止。

Resume 页面可用 Print / Save as PDF 生成简洁 PDF；没有虚假的下载链接。正式申请前请用本人确认过的教育经历与日期补全简历。

## 内容依据与待确认项

- 姓名暂采用对话中的 **Zhuodan Yin**。现有 Our Closet 公开记录还使用 **Zaria Yin**，正式使用时请本人确认全站显示名。此处未擅自替换为另一个名字。
- Our Closet 事实依据为账号现有仓库 README 和公开项目记录： https://github.com/24r14/Our-Closet 。团队成果与个人贡献分开，304 和 100 为物资数量，不是受益人数；第一名为团队展示，不是个人奖项。
- 研究页只呈现探索方向。未将对话中助手提到的 Nardi Lab、研究助理、TCM 研究、论文、DECA、投壶和支教写成已确认经历；拿到本人材料后再补。
- 个人手册和 How I Think 为依据本次对话起草的表达，需本人审阅，以确保代表自己的真实想法。
- 未知的学校、年级、毕业日期、成绩、语言熟练度、技能水平、邮箱和证书均未编造。
- Korean-Review 只提供现有仓库链接，不声称已完成产品或特定技术功能。
- 网站项目明确写明 AI 协助，未将制作过程描述为本人独立编码。
- 未复制原项目中的通讯截图或第三方姓名；未包含私人健康记录、住址、电话、课表或 host family。

## 新增照片与活动

- 用户上传了活动与做饭照片，并明确确认：手工活动是中秋活动里的一个环节，该环节全部内容由本人独立负责。网站使用 Mid-Autumn craft workshop 作为描述性标题；独立负责的范围限于手工环节，未写成整场中秋活动均由本人组织。日期、参与人数与活动正式名称尚未补写。
- 工作坊采用两张参与者制作过程照片；未把照片中的参与者认作网站作者，也未为他们添加姓名。
- About 使用用户出国后做饭照片中的餐桌、火锅和手工包子三张。只写已确认的做饭事实，未编写想家、请客或特殊节日的故事。
- assets/photos 中为原图按比例缩小、压缩后的网页版本，已去除 EXIF 等嵌入元数据。没有生成、修饰或替换照片内容。原始上传文件保持不变，网页排版使用 CSS 裁切显示，并可点击查看完整画面。
- 其余文化展台、舞蹈、峰会、志愿服务和 DECA 照片尚未发布，具体角色、活动关系或奖项信息仍待确认。

## 上线前的内容复核

确认姓名和英文文案；补充可公开的正式简历；只有在取得可公开的原始材料后再加入实验室职位、研究成果、日期、项目角色和照片。

## 验证

交付时的检查结果见同级交付说明（不需要上传到站点）。本网站不依赖服务器路由，所有七个栏目均为独立的 HTML 页面。
