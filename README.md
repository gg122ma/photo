# photo
# Wander Archive — 旅行摄影档案网站

一个多语言旅行摄影个人作品集网站，支持中/英/马来文三语切换，采用混沌瀑布流画廊布局，注重沉浸式视觉体验。

## 技术栈

- **前端**：原生 HTML / CSS / JavaScript（单文件）
- **字体**：Google Fonts（Cormorant Garamond + DM Mono）
- **图片资源**：Unsplash
- **版本管理**：GitHub

## 功能特性

- **三语言 i18n**：中文 / English / Bahasa Malaysia 无刷新全局切换
- **混沌瀑布流画廊**：6 列 CSS Grid，通过 `span` 列数和 `margin-top` 偏移制造参差错落感
- **懒加载 & 入场动画**：IntersectionObserver 驱动
- **自定义光标**：`requestAnimationFrame` 缓动跟随，hover 时放大切换 `mix-blend-mode`
- **Lightbox 图片查看器**：支持键盘导航和图片计数器
- **滚动进度条**：顶部渐变进度指示
- **导航栏**：滚动时自动隐藏/显示
- **响应式**：适配移动端汉堡菜单

## 项目状态

> ⚠ 本项目仍在开发中，部分功能尚未完成。

当前已完成：
- 首页（Hero + 精选展示）
- 画廊页（瀑布流布局）
- 关于页（个人信息 + 价值观 + 旅行足迹）
- 三语言切换系统
- Lightbox 图片查看器

待完成：
- 更多图片数据接入
- 细节优化与性能调优

## 开发工具

| 工具 | 用途 |
|------|------|
| MiMo v2.5 Pro | 代码生成、布局设计、交互逻辑 |
| Gemini AI | 知识查询、方案探索 |
| Claude Code | 代码审查、多语言架构设计 |

本项目由零编程基础通过 AI 辅助独立完成，AI 承担了布局设计、交互逻辑、多语言架构的代码生成与调试。
