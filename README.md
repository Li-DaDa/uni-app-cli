# ts-uni-mini

## 安装
```
yarn install
```

## 启动小程序开发环境
### 启动项目，实时编译
```
yarn dev:mp-weixin
```
### 打开微信开发者工具，连接项目
* 启动微信开发者工具
* 导入项目，项目路径 /dist/mp-weixin/

## git 提交规范
### git提交格式
```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

### type类型
* feat：新功能、新特性
* fix：修改bug
* perf：更改代码，以提高特性
* refactor：代码重构
* docs: 文档修改
* style: 代码格式修改, 注意不是 css 修改（例如分号修改）
* test: 测试用例新增、修改
* build: 影响项目构建或依赖项修改
* revert: 恢复上一次提交
* ci: 持续集成相关文件修改
* chore: 其他修改（不在上述类型中的修改）
* release: 发布新版本
* workflow: 工作流相关文件修改

## eslint规范
遵守 airbnb 规范

## stylelint规范
遵守 stylelint-config-standard
