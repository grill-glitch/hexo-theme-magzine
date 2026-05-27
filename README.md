<div align="center">
  <h1>Magzine 主题</h1>
</div>

![预览图](https://github.com/user-attachments/assets/7bf5964e-9dfe-41f6-a281-3568bd5807ef)

<div align="center">
  <p>
    一款现代化的杂志风格 Hugo 主题，大屏支持，简洁、优雅、快速
  </p>
</div>

## 预览
👉 我的[博客](https://2am.top)

## 使用手册
👉 [使用手册](https://2am.top/2026/01/28/magzine%E4%B8%BB%E9%A2%98%E6%8C%87%E5%8C%97/)

## 功能特性

-   **现代化设计**：简洁、极简的美学设计，流畅的交互体验
-   **杂志式布局**：动态文章卡片，支持多种大小和位置
-   **响应式设计**：适配各种设备，支持超大屏幕
-   **高度可定制**：丰富的主题配置选项（颜色、字体、布局等）
-   **性能优化**：平滑滚动、动画优化、内置搜索索引生成
-   **AI 摘要**：接入 DeepSeek 摘要功能
-   **短代码 (Shortcodes)**：移植了常用标签外挂，支持注脚、时间轴、隐藏内容、标签、按钮等

## 安装方法

1.  将主题作为子模块添加到您的 Hugo 项目：

``` bash
git submodule add https://github.com/grill-glitch/hexo-theme-magzine.git themes/magzine
```

2.  在您的 `hugo.yaml` (或 `hugo.toml`) 文件中设置主题：

``` yaml
theme: magzine
```

3.  复制主题中的 `hugo.yaml` 示例配置到您的站点根目录进行自定义。

## 站点配置示例 (hugo.yaml)

``` yaml
params:
  colors:
    accent: '#ff6b6b' # 主题色
  hero:
    enable: true
    typing_text: "天接云涛连晓雾，星河欲转千帆舞"
  author_card:
    enable: true
    name: "作者名"
    bio: "自我介绍"
  ai_summary:
    enable: true
    api_key: "your-api-key"
```

## 贡献指南

1.  Fork 本仓库
2.  创建功能分支
3.  编写代码并提交
4.  提交 Pull Request

## 开源协议
本主题使用 **MIT** 协议开源。

## 致谢

-   [Hugo](https://gohugo.io/) 静态网站生成器
-   [Font Awesome](https://fontawesome.com/) 图标
