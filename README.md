# DSAPS by Java

PTA《数据结构与算法题目集（中文版）》的题解与 Java 实现说明。

本仓库使用 Docsify 发布为静态文档站点，页面风格参考 [DSAPS by C](https://pta-program.github.io/DSAPS_article_by_C/)。打开左侧导航即可浏览全部题目，也可以通过搜索框按题号或关键词检索。

## 内容

- [函数题](./函数题/)：12 道函数实现题的题意、接口说明、思路和 Java 代码示例。
- [编程题](./编程题/)：53 道完整程序题的题意、输入输出、算法分析和 Java 代码示例。

共收录 65 道题目。每个 Markdown 文件都是一篇独立题解，代码块保留了适合提交和学习的 Java 示例。

## 在线阅读

GitHub Pages 启用并完成首次 Actions 部署后，站点地址为：

```text
https://pta-program.github.io/DSAPS_article_by_java/
```

站点提供以下功能：

- 左侧导航覆盖全部 65 个题目标题；
- 题号和关键词搜索；
- 上一题 / 下一题导航；
- 代码复制、图片缩放和 Mermaid 流程图；
- 页面右下角暗色模式切换，并记住用户选择。

## 首次启用 GitHub Pages

仓库管理员需要在 GitHub 打开 `Settings` → `Pages`，将 `Build and deployment` 的 `Source` 设为 `GitHub Actions`。保存后重新运行 `Deploy Docsify to GitHub Pages` 工作流，或向 `main` 推送新的提交。

## 本地预览

在仓库根目录运行：

```bash
python3 -m http.server 8899 --bind 127.0.0.1
```

然后访问 <http://127.0.0.1:8899/>。Docsify、Mermaid 和插件通过 CDN 加载，首次打开页面需要网络连接。

## 目录结构

```text
DSAPS_article_by_java/
├── index.html                  # Docsify 入口与站点样式
├── _sidebar.md                 # 全部题目导航
├── .nojekyll                   # GitHub Pages 静态资源标记
├── .github/workflows/pages.yml # GitHub Actions 部署流程
├── 函数题/                     # 12 篇函数题题解
├── 编程题/                     # 53 篇编程题题解
└── README.md                  # 站点首页
```

## 许可

题目内容版权归 PTA 及原作者所有。本仓库仅用于学习、整理和交流。
