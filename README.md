<h4 align="right">
  <strong>简体中文</strong> | <a href="https://github.com/simongino/bob-plugin-qwen-translator/blob/main/docs/README_EN.md">English</a>
</h4>

<div>
  <h1 align="center">DeepSeek Translator Bob Plugin</h1>
  <p align="center">
    <a href="https://github.com/simongino/bob-plugin-qwen-translator/releases" target="_blank">
        <img src="https://github.com/simongino/bob-plugin-qwen-translator/actions/workflows/release.yaml/badge.svg" alt="release">
    </a>
    <a href="https://github.com/simongino/bob-plugin-qwen-translator/releases">
        <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/simongino/bob-plugin-qwen-translator?style=flat">
    </a>
    <a href="https://github.com/simongino/bob-plugin-qwen-translator/releases">
        <img alt="GitHub Repo stars" src="https://img.shields.io/badge/deepseek-bob-orange?style=flat">
    </a>
    <a href="https://github.com/simongino/bob-plugin-qwen-translator/releases">
        <img alt="GitHub Repo stars" src="https://img.shields.io/badge/langurage-JavaScript-brightgreen?style=flat&color=blue">
    </a>
  </p>
</div>

## 简介

这是一个基于 DeepSeek API 的 Bob 翻译插件。Bob 社区版本目前缺乏基于大语言模型的翻译服务，这个插件填补了这个空白，为用户提供了更智能、更自然的翻译体验。

### 版本兼容性

| 版本类型 | 支持情况 | 特别说明 |
|---------|----------|----------|
| Bob 社区版 | ✓ 支持 | - 版本要求 >= 0.50<br>- 不支持流式响应 |
| Bob 商店版 | ✓ 支持 | 完整支持所有功能 |

### 核心优势

| 特性 | 描述 |
|------|------|
| 智能翻译 | - 基于 DeepSeek 大语言模型<br>- 翻译结果自然流畅<br>- 特别适合长句和专业术语 |
| 文本润色 | - 支持同语言间的文本优化<br>- 提供更优美的表达方式 |
| 高性能 | - 采用最新的 DeepSeek Chat 模型<br>- 响应速度快 |
| 易用性 | - 安装配置简单<br>- 完全免费（仅需 DeepSeek API Key）|

### 语言模型

目前默认使用 `DeepSeek Chat` 模型：
- 响应速度快，接近实时翻译体验
- 翻译质量优秀
- API 调用成本较低

更多模型详情请参考[官方文档](https://platform.deepseek.com/)。

## 使用方法

1. 安装 [Bob](https://bobtranslate.com/guide/#%E5%AE%89%E8%A3%85) (要求版本 >= 0.50)

2. 下载插件: [deepseek-translator.bobplugin](https://github.com/simongino/bob-plugin-qwen-translator/releases/latest)

3. 安装插件：双击下载的 .bobplugin 文件

4. 获取 API Key：
   - 访问 [DeepSeek 平台](https://platform.deepseek.com/)
   - 注册/登录账号
   - 在控制台中获取 API Key

5. 配置插件：
   - 打开 Bob 偏好设置
   - 选择服务栏
   - 找到 DeepSeek Translator
   - 将获取的 API Key 填入配置框

6. 可选配置：
   - 安装 [PopClip](https://bobtranslate.com/guide/integration/popclip.html) 实现划词翻译
   - 配置快捷键，提高使用效率

## 致谢

本项目的诞生离不开以下优秀项目的启发：

- [bob-plugin-openai-translator](https://github.com/yetone/bob-plugin-openai-translator) - 提供了基础的项目架构和灵感
- [bob-plugin-claude-translator](https://github.com/jtsang4/bob-plugin-claude-translator) - 提供了优秀的功能实现参考

特别感谢这些项目的作者们对开源社区的贡献！
