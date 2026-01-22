# 食品法规数字化 Food Legislation Digitalization

A programme for digitalize Food Legislation. 一个食品法规数字化项目。

## 目标

1. 使食品法规无论在桌面端还是移动端、无论不同部门在不同年代发布的法规都有良好且统一的阅读体验
2. 使标准文本可以轻易复制，并且不会因为pdf的文档结构导致复制出的文本带有奇怪的换行
3. 通过强行OCR绕过部分标准文本复制后变成乱码的问题
4. 可以利用RAG等技术生成知识库
5. 正文可以直接复制进钉钉文档、飞书文档、Notion等软件中，完整保留格式，可以利用上述软件直接检索全文或建立AI知识库
6. 为每个法规建立基础信息表，包括发文号、发布日期、实施日期、发布链接等

## 文件夹说明

- digitalFoodLegislation：Markdown格式的法规文件，可以直接打开，也可以下载到本地
- HTML（计划中）：将Markdown格式的法规文件导出为HTML格式。如果你没有Markdown编辑器或不知道什么是Markdown文件，请下载这个文件夹中的文件。请下载后打开本地文件。
- RAW：相关部门发布的原始法规文件

## 使用方法

- 请pull整个库或者下载整个库的zip文件。

## 应用

- [Notion]([Notion](https://www.notion.so/2e08910c52758116abc9f6db9a90ae47?v=2e08910c5275812eb8b3000c9d079603))：html表格无法正确渲染，只能显示为代码

- [Google NotebookLM](https://notebooklm.google.com/notebook/5676c005-e2a8-4f22-a236-90cb25e275d6)：完全无法显示html表格

- [infiniflow/ragflow](https://github.com/infiniflow/ragflow)：可以正确显示html表格

<img width="1080" height="1260" alt="image" src="https://github.com/user-attachments/assets/5e51ce98-caa9-4e94-acba-384217ef5182" />

<img width="1278" height="1279" alt="image" src="https://github.com/user-attachments/assets/6aa8c1bb-9e84-4269-adff-8ec97f38b2fb" />



