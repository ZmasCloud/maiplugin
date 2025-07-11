
# 🚀 麦麦插件整合仓库

## 介绍
本仓库仅用于整合麦麦插件 v0.1。

> ⚠️ 当前暂未适配 v0.2 版本插件。

## 主旨
本仓库旨在为用户提供一个集中、便捷的插件下载与使用平台。

## 贡献指南

欢迎各位开发者提交您的插件！请确保提交的内容符合以下要求：

### 访问仓库。

### fork本仓库


## 添加插件文件
📌 **请将修改后的about.md文件 PR 提交至 `master` 分支！**

请在 about.md 文件末尾添加以下内容：

| 插件名称       | [gitee/github](仓库url) | [作者主页](主页url) |
|----------------|------------------------|-------------------|
```markdown
 | 插件名称       | [gitee/github](仓库url) | [作者主页](主页url) |
```
>请确保仓库按照以下目录：
>- 插件目录/  
>   - actions/  
>     - 插件文件.py  
>   - init.py  
>>请自行修改markdown格式（对齐）！

提交你的about.md到本地仓库。
法1
```bash
git add .
git commit -m "添加插件xxxxxx"
git push origin main
```
法2
前往你的仓库
点击pull requests（pr）
提交pr
等待4位ai审核通过


## 当前进度
- [ ] 适配 v0.2 插件
- [x] GitHub 仓库同步
- [ ] 命令系统插件
- [x] 支持 PR 提交插件

## 注意事项
- 所有插件需经过审核后合并。
- 建议对插件进行测试是否可调用、发送后再提交。
