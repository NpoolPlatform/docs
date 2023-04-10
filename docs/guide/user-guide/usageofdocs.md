## Docs Usage
> 本文旨在让大家规范地提交文档至本仓库。访问地址：https://npoolplatform.github.io/docs

## 文档提交流程
- 下载仓库至本地
- 使用markdown语法编辑文档
- 提交pull request至仓库

## 文档规范
- 网站样式采用docsify语法
- 命名规范
  - 使用英文无空格命名
  - 文档名以.md结尾
  - 命名语义清楚
- 文档内容需要使用markdown语法
- 目录规范
  - 设计文档存放在对应产品的designs目录(如```sass/designs```)
  - 服务说明文档存放在对应产品的services目录(如```sass/services```)
  - 添加新增文档访问链接至对应目录的sidebar(如```sass/_sidebar.md```)

## 编辑工具
- windows用户在clone仓库后可使用Sublime Text或vscode编辑文档
  - Sublime Text需要安装MarkdownPreview插件
- linux用户可在clone仓库后通过docsify编译访问```http://localhost:3000```进行预览
```bash
npm i docsify-cli -g
docsify serve docs
```
