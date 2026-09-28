# Source Materials

本目录用于保存《计算思维》教材的原始依据文件和上传建议。

## 建议纳入 GitHub 的源文件

### 1. 课程 PDF

建议保存：

`source/计算思维（初阶）18次课程大纲.pdf`

用途：

- 核对课程原始表述
- 核对课题顺序
- 核对培养目标
- 后续课程调整时做版本对比

同时维护：

- `references/CURRICULUM.md` — 适合 Skill 读取和维护的结构化摘要

PDF 是原始依据，CURRICULUM.md 是可执行摘要，两者职责不同。

### 2. 官方吉祥物源图

建议保存到：

`references/mascot/source-images/`

推荐文件名：

- `tiangcheng-standard.png`
- `yangguang-standard.png`
- `xiaoyi-standard.png`
- `tech-extension-reference.png`

用途：

- 角色一致性基准
- 新动作生成参考
- 后续角色规范校验

## 是否所有图片都应该进仓库？

不需要。

建议进入 GitHub：

- 官方标准形象
- 官方角色设定图
- 学校 VI 原稿
- 经确认的关键扩展形象
- 最终采用的教材通用素材

不建议把所有 AI 尝试稿、废稿和中间版本都提交到主仓库。

## 文件大小建议

普通小型 PNG / PDF 可以直接使用 Git 管理。

如果后续出现：

- 大量高分辨率 PSD
- 大量 TIFF
- 大型设计源文件
- 单文件几十 MB 以上
- 数百张高分辨率图片

建议改用 Git LFS 或单独的素材存储方案，避免仓库体积快速膨胀。

## 当前状态

以下课程源文件已上传：

- `计算思维（初阶）18次课程大纲.pdf`

课程 PDF 与官方吉祥物图均已作为项目核心源文件保留。

主 Skill 不复制二进制内容，而是通过：

- `references/CURRICULUM.md`
- `references/VISUAL-GUIDE.md`
- `references/mascot/MASCOT-GUIDE.md`

建立可执行的结构化规则。
