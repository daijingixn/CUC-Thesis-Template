# CUC-Thesis-Template
本人已使用此模版完成中国传媒大学硕士以及博士论文的撰写，盲审以及图书馆提交均未被质疑格式问题。
模版的最初版本来源于https://github.com/AmnesiaBeing/CUC-Thesis-Template。
# 模版结构说明
.
├── .vscode                 Visual Studio Code配置目录
├── 中国传媒大学论文要求.pdf    来自研究生院网站上的毕业论文细则
├── 示例.pdf                 示例pdf，也是模板中已有代码生成的
├── bib                     建议使用文献管理工具管理阅读过的文献，譬如Zotero
│   └── reference.bib       使用文献管理工具生成的bib文件
├── chapters                正文各章节，自行模仿修改为自己的内容
├── configs                 一些配置信息
│   ├── caption.tex         图、表、代码题注
│   ├── fonts.tex           字体配置（引用了fonts文件夹内的字体）
│   ├── heading.tex         各级标题样式
│   ├── image.tex           图片路径配置
│   ├── layout.tex          页面布局（包括内容占A4纸的位置、页眉页脚、定义不同的页面样式等）
│   ├── listings.tex        代码配置（设置代码字体为等宽字体FiraCode，代码边框）
│   ├── misc.tex            杂项（不知道怎么分类）
│   ├── packages.tex        引用的一些宏包
│   ├── reference.tex       参考文献样式设置
│   ├── table.tex           表格设置（空文件）
│   └── toc.tex             目录设置
├── cucthesis.cls           cls模板文件
├── cucthesis.tex           模板主入口（增删章节后需要在这里修改）
├── cucthesis-detail-abstract.tex 详细摘要主入口（主要内容只是封面页和详细摘要）
├── figures                 图片文件
│   ├── blackwhite          黑白图片
│   └── colorful            彩色图片
├── fonts                   使用到的字体文件夹（可忽略）
├── out                     输出文件夹
├── pages                   页面
│   ├── abstract-chn.tex    中文摘要
│   ├── abstract-eng.tex    英文摘要
│   ├── auth-claim.tex      原创性声明
│   ├── cover-detail-abstract.tex 详细摘要封面
│   ├── cover.tex           封面
│   ├── detail-abstract.tex 详细摘要内容
│   ├── reference.tex       参考文献
│   ├── thanksto.tex        致谢
│   └── toc.tex             目录
└── Readme.md               本说明文档


# 使用此模版的一些常见问题
## 如何使用该模版？
