# The Art of HPC 中文翻译项目 📚🌏

[![CC BY 4.0 License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)

本仓库致力于 Victor Eijkhout 开源著作 [The Art of HPC](https://github.com/VictorEijkhout/TheArtofHPC_pdfs) 系列的中文翻译，推动高性能计算（HPC）知识在中文社区的普及与发展。

## 项目简介

- **原作者**：Victor Eijkhout
- **原书仓库**：[TheArtofHPC_pdfs](https://github.com/VictorEijkhout/TheArtofHPC_pdfs)
- **原书官网**：[theartofhpc.com](https://theartofhpc.com/)
- **开源协议**：CC-BY 4.0 🆓

> 💡本项目所有翻译内容均基于原作者授权的 CC-BY 4.0 协议，欢迎大家自由使用，但请注明原作者及本项目出处。
> 💡 为了便于在 GitHub 上存储和下载，本项目中的所有 PDF 文件均已做最大程度的体积优化，尽量保证内容完整的同时减小文件大小，方便大家获取和使用。

## 翻译书籍目录 📖

| 卷册 | 原版文件名 | 翻译版文件名 |
|------|------------|--------------|
| vol1 | [intro-to-hpc.pdf](vol1/intro-to-hpc.pdf) | [intro-to-hpc-zh.pdf](vol1/intro-to-hpc-zh.pdf) | 
| vol2 | [parallel-programming.pdf](vol2/parallel-programming.pdf) | [parallel-programming_zh.pdf](vol2/parallel-programming_zh.pdf) | 
| vol3 | [Intro-sci-programming-book.pdf](vol3/Intro-sci-programming-book.pdf) | [Intro-sci-programming-book-zh.pdf](vol3/Intro-sci-programming-book-zh.pdf) | 
| vol3 | [programming-projects-book.pdf](vol3/programming-projects-book.pdf) | [programming-projects-book-zh.pdf](vol3/programming-projects-book-zh.pdf) | 
| vol4 | [hpc-tutorials.pdf](vol4/hpc-tutorials.pdf) | [hpc-tutorials_zh.pdf](vol4/hpc-tutorials_zh.pdf) | 

## 目录结构 🗂️

```
.
├── vol1/                  # 第一卷：HPC导论
│   ├── intro-to-hpc.pdf         # 原版
│   └── intro-to-hpc-zh.pdf      # 中文版
├── vol2/                  # 第二卷：并行编程
│   ├── parallel-programming.pdf       # 原版
│   └── parallel-programming_zh.pdf    # 中文版
├── vol3/                  # 第三卷：科学编程
│   ├── Intro-sci-programming-book.pdf      # 原版
│   ├── Intro-sci-programming-book-zh.pdf   # 中文版
│   ├── programming-projects-book.pdf        # 原版
│   └── programming-projects-book-zh.pdf     # 中文版
└── vol4/                  # 第四卷：HPC教程
    ├── hpc-tutorials.pdf       # 原版
    └── hpc-tutorials_zh.pdf    # 中文版
```

## 贡献指南 🤝

欢迎任何人参与本项目的翻译、校对和改进！贡献流程如下：

1. **Fork 本仓库**，新建分支进行翻译或修订
2. **翻译流程**：
   - 选择要翻译的章节
   - 创建新分支：`git checkout -b feat/translate-chapterX`
   - 提交翻译内容
3. **提交规范**：
   ```bash
   git commit -m "feat: 添加第X章翻译"
   ```
4. **创建 Pull Request**：
   - 描述翻译内容和修改点
   - 关联相关Issue（如有）
5. **术语与风格**：
   - 统一采用学术界主流术语
   - 保持技术准确性，优化中文表达
   - 所有代码注释均需翻译
   - 参考[术语对照表](术语对照表.md)

> 📢 如有疑问或建议，请在 [Issues 区](https://github.com/your-repo/issues) 留言讨论

特别感谢 Victor Eijkhout 教授开源原著！

## 协议声明 📄

本项目遵循 [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh) 协议，转载请注明原作者及本项目地址。

---

> ⭐ 如果本项目对您有帮助，欢迎 Star 支持！  
> 🍴 欢迎 Fork 参与翻译改进  
> 📢 分享给更多 HPC 爱好者！