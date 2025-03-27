# UPC CV Template

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)

## 简介 | Introduction

这是一个基于 LaTeX 的中国石油大学（华东）简历模板。该模板旨在为中国石油大学的学生提供一个专业、美观的个人简历模板。

This is a LaTeX-based CV template for China University of Petroleum (East China). This template aims to provide UPC students with a professional and aesthetically pleasing personal resume template.

### 特点 | Features

本模板基于 [WHU 中文 CV 模板](https://www.overleaf.com/latex/templates/whuwu-han-da-xue-zhong-wen-jian-li-mo-ban/dbkvxrqjmzpd)以及 [NPU 中文 CV 模板](https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx)，并在原有内容的基础上进行了以下修改：

This template is based on the [WHU Chinese CV Template](https://www.overleaf.com/latex/templates/whuwu-han-da-xue-zhong-wen-jian-li-mo-ban/dbkvxrqjmzpd) and [NPU Chinese CV Template](https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx), with the following modifications:

- 更改了照片和个人信息栏位的相对位置
  
  Changed the relative position of photo and personal information sections

- 更改了部分段落的格式；使用 `itemize` 整理每个项目的说明
  
  Modified certain paragraph formats; used `itemize` to organize the description of each item

- 更改了校徽图标
  
  Updated the university logo

- 调整了装饰图案的色彩风格
  
  Adjusted the color scheme of decorative patterns

## 预览 | Preview

![CV Preview](./docs/CV_preview.pdf)

## 使用方法 | Usage

### 在线使用 | Online Usage

1. 访问 [Overleaf](https://www.overleaf.com/) 并创建一个新项目
   
   Visit [Overleaf](https://www.overleaf.com/) and create a new project

2. 上传模板文件
   
   Upload the template files

3. 编辑 `main.tex` 中的内容，自定义你的简历
   
   Edit the content in `main.tex` to customize your resume

### 本地使用 | Local Usage

1. 确保你已安装 LaTeX 环境（推荐 [TeX Live](https://www.tug.org/texlive/) 或 [MiKTeX](https://miktex.org/)）
   
   Ensure you have a LaTeX environment installed (recommended: [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/))

2. 克隆或下载此仓库
   
   Clone or download this repository

3. 编辑 `main.tex` 中的内容，对文档样式和内容进行修改
   
   Edit the content in `main.tex` to modify document style and content

4. 使用 `XeLaTeX` 或 `LuaLaTeX` 编译
   
   Compile using `XeLaTeX` or `LuaLaTeX`

   ```bash
   xelatex main.tex
   ```
   或 | or
   ```bash
   lualatex main.tex
   ```

## 文件结构 | File Structure

```
UPC-CV-Template/
├── main.tex           # 主 LaTeX 文件 | Main LaTeX file
├── upc-logo.png       # 中国石油大学（华东）校徽 | UPC logo
├── photo.png          # 示例照片 | Example photo
├── reference.bib      # 参考文献 BibTeX 文件 | Bibliography BibTeX file
└── README.md          # 本文档 | This document
```

## 自定义 | Customization

在 `main.tex` 中，你可以自定义以下内容：

In `main.tex`, you can customize the following:

- 个人信息 | Personal Information
- 教育背景 | Education Background
- 科研成果 | Research Achievements
- 项目与教学 | Projects and Teaching Experience
- 技能特长 | Skills
- 兴趣爱好 | Interests

## 许可证 | License

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解更多详情。

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 致谢 | Acknowledgements

- [WHU 中文 CV 模板](https://www.overleaf.com/latex/templates/whuwu-han-da-xue-zhong-wen-jian-li-mo-ban/dbkvxrqjmzpd)
- [NPU 中文 CV 模板](https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx)
