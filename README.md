# Mozc + UT Dictionary Build

A personal fork and dictionary-integrated build based on the original Mozc project.

This repository only integrates additional dictionary data into Mozc.
All Mozc source code comes from the original Google Mozc project.

---

# 简介

这是基于 Google Mozc 的个人 Fork 项目。

本项目主要工作：

- Fork 原版 Mozc 源码
- 使用词库整合工具生成扩展词库
- 将 UT/SKK 等词库数据整合进 Mozc
- 使用 GitHub Actions 自动构建 Windows MSI 安装包

除此之外没有对 Mozc 核心功能进行修改。

## 词库来源与工具

本项目使用以下开源项目进行词库整合：

- mozcdic-ut-skk-jisyo  
  https://github.com/utuhiro78/mozcdic-ut-skk-jisyo

- merge-ut-dictionaries  
  https://github.com/utuhiro78/merge-ut-dictionaries

上述项目用于生成和整合 Mozc 可使用的扩展词典格式。

感谢相关开源项目作者的工作。

## 说明

本项目不是 Google 官方产品，也不是 Mozc 官方维护版本。

Mozc 原始项目：

https://github.com/google/mozc

所有 Mozc 源码、第三方组件以及词库数据均遵循其各自原始许可证。

## 构建

Windows 版本通过 GitHub Actions 自动构建。

构建产物可在：

- GitHub Actions Artifacts
- Releases 页面

获取。

## License

Mozc 本体遵循原项目 BSD 3-Clause License。

额外整合的词库数据遵循其各自来源许可证。
