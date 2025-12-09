好的，这是关于 **XDUTS (Xidian University TeX Suite)** 的详细中文翻译和说明：

------



## 🎓 XDUTS (西安电子科技大学 TeX 套件) 中文说明



**XDUTS (Xidian University TeX Suite)** 是一个专为**西安电子科技大学**本科生/研究生设计的 **LaTeX3 文档类和宏包套件**。它可以在 Windows、macOS、GNU/Linux、Overleaf 和 TeXPage 等环境下使用 **XeLaTeX** 编译器进行编译。它旨在排版**开题报告、学位论文**及其他文档。



### 📦 XDUTS 当前包含的宏包和文档类



XDUTS 目前包含以下组件：

- **xdufont.sty**： 西安电子科技大学字体宏包。
- **xduugtp.cls**： 西安电子科技大学本科生开题报告文档类。
- **xdupgthesis.cls**： 西安电子科技大学研究生学位论文文档类。
- **xduugthesis.cls**： 西安电子科技大学本科生学位论文文档类。

**未来计划**增加以下文档类：

- **xdupgtp.cls**： 西安电子科技大学研究生开题报告文档类。



### 🛠️ 环境准备





#### TeX Live/MacTeX 用户



如果您使用 TeX Live 或 MacTeX，请确保已安装**最新版本**。然后运行以下命令来更新所有宏包：

- **`tlmgr update --all --self`**

  > 💡 **注意：** 在 Windows 上，可能需要以**管理员身份**运行命令提示符；在 macOS 或 GNU/Linux 上，可能需要使用 `sudo` 运行此命令。



#### MiKTeX 用户



如果您使用 MiKTeX，运行以下命令来更新所有已安装的宏包：

- **`miktex packages update`**



### 📥 安装方法



您可以通过 **CTAN** 或 **GitHub** 安装 XDUTS。通常，**CTAN 更新 XDUTS 较慢**。如果希望使用最新版本，建议从 **GitHub** 获取。



#### 从 CTAN 安装



**对于 TeX Live/MacTeX/MiKTeX 本地安装：**

完成环境准备后，运行以下命令即可打开 XDUTS 的使用文档（**`xduts.pdf`**）：

- **`texdoc xduts`**

**对于 Overleaf/TeXPage 用户：**

如果您已在本地安装 LaTeX 发行版，可以按照下述方法获取文档类/宏包文件和文档。否则，您需要从 **CTAN 下载**文档类/宏包文件和文档，然后将这些文件**上传**到您的 Overleaf/TeXPage 项目中。



#### 从 GitHub 安装（获取最新版）



完成环境准备后，下载此存储库，然后在下载的文件夹中运行以下命令来获取文档类/宏包文件和文档：

1. **`xetex xduts.ins`**
2. **`l3build doc`**



### 🔄 更新



更新过程与安装过程相同，只需按照上述步骤操作即可。



### 📌 使用说明



为了更好地使用 XDUTS，请务必**从头开始仔细阅读文档**，即 **`xduts.pdf`** 文件。



### 📜 注意事项



- **`xdulogo.pdf`** 文件应放置在与您使用的文档类文件（例如 `xduugthesis.cls`）**相同的目录**中。



### ⚖️ 许可



XDUTS 遵循 **LaTeX Project Public License (LPPL) 版本 1.3c 或更高版本**。

------

希望这份翻译能够帮助您顺利开始使用 XDUTS 模板！

**您现在是想让我帮您查找最新的 XDUTS 文档 (`xduts.pdf`)，还是想了解如何在您的 LaTeX 文件中配置它？**