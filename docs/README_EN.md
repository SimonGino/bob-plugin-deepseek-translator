<h4 align="right">
  <a href="https://github.com/simongino/bob-plugin-qwen-translator/blob/main/README.md">简体中文</a> | <strong>English</strong>
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

## Introduction

This is a Bob translation plugin powered by the DeepSeek API. While Bob's community version lacks LLM-based translation services, this plugin fills this gap by providing a more intelligent and natural translation experience.

### Version Compatibility

| Version | Support | Notes |
|---------|----------|--------|
| Bob Community Edition | ✓ Supported | - Version requirement >= 0.50<br>- No streaming response support |
| Bob Store Edition | ✓ Supported | Full feature support |

### Core Advantages

| Feature | Description |
|---------|-------------|
| Smart Translation | - Powered by DeepSeek LLM<br>- Natural and fluent translation results<br>- Especially suitable for long sentences and technical terms |
| Text Polishing | - Supports text optimization within the same language<br>- Provides more elegant expressions |
| High Performance | - Uses the latest DeepSeek Chat model<br>- Fast response time |
| User-Friendly | - Simple installation and configuration<br>- Completely free (only requires DeepSeek API Key) |

### Language Model

Currently uses the `DeepSeek Chat` model by default:
- Near real-time translation experience
- Excellent translation quality
- Cost-effective API calls

For more model details, please refer to the [official documentation](https://platform.deepseek.com/).

## Usage

1. Install [Bob](https://bobtranslate.com/guide/#%E5%AE%89%E8%A3%85) (version >= 0.50)

2. Download plugin: [deepseek-translator.bobplugin](https://github.com/simongino/bob-plugin-qwen-translator/releases/latest)

3. Install plugin: Double-click the downloaded .bobplugin file

4. Get API Key:
   - Visit [DeepSeek Platform](https://platform.deepseek.com/)
   - Register/Login to your account
   - Obtain API Key from the console

5. Configure plugin:
   - Open Bob Preferences
   - Select Services tab
   - Find DeepSeek Translator
   - Enter your API Key in the configuration box

6. Optional setup:
   - Install [PopClip](https://bobtranslate.com/guide/integration/popclip.html) for text selection translation
   - Configure hotkeys for improved efficiency

## Acknowledgments

This project was inspired by these excellent projects:

- [bob-plugin-openai-translator](https://github.com/yetone/bob-plugin-openai-translator) - Provided the foundational architecture and inspiration
- [bob-plugin-claude-translator](https://github.com/jtsang4/bob-plugin-claude-translator) - Offered excellent functional implementation references

Special thanks to the authors of these projects for their contributions to the open source community!
