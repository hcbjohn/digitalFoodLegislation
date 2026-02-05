# 食品法规数字化 Food Legislation Digitalization

A programme for digitalize Food Legislation. 一个食品法规数字化项目。

## 目标

1. 使食品法规无论在桌面端还是移动端、无论不同部门在不同年代发布的法规都有良好且统一的阅读体验。当然我不建议你在手机上看法规，要么你连电脑都没有，要么你在休息时间还要处理工作。
2. 使标准文本，可以轻易复制，并且不会因为pdf的文档结构导致复制出的文本带有奇怪的换行。
3. 所有图片均转换为BASE64代码，一个.md文件包含完整的信息。
4. 复杂的表格采用html代码实现。
5. 可以利用RAG等技术生成知识库。
6. 正文可以直接复制进钉钉文档、飞书文档、Notion等软件中，完整保留格式，可以利用上述软件直接检索全文或建立AI知识库。
7. 为每个法规建立基础信息表，包括发文号、发布日期、实施日期、发布链接等。

## 文件夹说明

- digitalFoodLegislation：Markdown格式的法规文件，可以直接打开，也可以下载到本地
- HTML（计划中）：将Markdown格式的法规文件导出为HTML格式。如果你没有Markdown编辑器或不知道什么是Markdown文件，请下载这个文件夹中的文件。请下载后打开本地文件。
- RAW：相关部门发布的原始法规文件

## 使用方法

- 请pull整个库或者下载整个库的zip文件，解压到任意位置。
- 可以使用任意Mrakdown的软件打开。这个软件需要支持将html代码渲染为表格、将BASE64代码渲染为图片。推荐使用Obsidian和Typedown。
- 如果你不知道什么是Mrakdown，请下载后直接打开html文件，电脑自带的浏览器就能打开。
- 你可以将所有文件导入至AI知识库。

### Obsidian

打开本地仓库，将文件夹作为仓库打开。

### Typedown

文件>>打开文件夹

### Ragflow

按照官方教程部署好以后，将所有文件上传至知识库就行了，注意配置好文件类型、自由度等参数。

### Notion

添加页面>>数据库>>文档中心，然后用本地Mrakdown软件依次将文档内信息复制进每条数据库记录中。

我不推荐使用Notion，除了导入麻烦外，还有以下缺点：

- 需要魔法上网
- 无法渲染html代码

<img width="1080" height="1260" alt="image" src="https://github.com/user-attachments/assets/5e51ce98-caa9-4e94-acba-384217ef5182" />

<img width="1278" height="1279" alt="image" src="https://github.com/user-attachments/assets/6aa8c1bb-9e84-4269-adff-8ec97f38b2fb" />



