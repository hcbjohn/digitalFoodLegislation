# 食品法规数字化 Food Legislation Digitalization

A programme for digitalize Food Legislation. 一个食品法规数字化项目。

## 目标

1. 无论在桌面端还是移动端、无论不同部门在不同年代发布的法规都有良好且统一的阅读体验。当然我不建议你在手机上看法规，天选牛马才会在手机上看法规。
2. 使标准文本，可以轻易复制，并且不会因为pdf的文档结构导致复制出的文本带有奇怪的换行。
3. 收录的pdf或doc均为主管部门发布的原文。
5. 可以利用RAG等技术生成知识库。
6. 正文可以直接复制进钉钉文档、飞书文档、Notion等软件中，可以利用上述软件直接检索全文或建立AI知识库。
7. 为每个法规建立元数据，包括发文号、发布日期、实施日期、发布链接等。

## 编码规则

1. 法规中的章采用一级标题，节采用二级标题，条采用三级标题。但是早年的法规编号混乱，无法兼顾所有情况。
2. 复杂表格采用html编码
3. 图片采用BASE64编码

## 使用方法

- 请pull整个库或者下载整个库的zip文件，解压到任意位置。
- 可以使用任意Mrakdown的软件打开。这个软件需要支持将html代码渲染为表格、将BASE64代码渲染为图片。推荐使用Obsidian和Typedown。
- 如果你不知道什么是Mrakdown，请下载后直接打开html文件，电脑自带的浏览器就能打开。
- 你可以将所有文件导入至AI知识库或建立本地的法规库。

### 一个法规库的示例

https://www.notion.so/463255/2e08910c52758116abc9f6db9a90ae47?v=2e08910c5275812eb8b3000c9d079603&source=copy_link

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



