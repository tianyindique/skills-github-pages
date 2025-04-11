---
title: "the-use-of-custom-attachment-location"
date: 2025-04-11
---
#### 插件的github: [github地址](https://github.com/RainCat1998/obsidian-custom-attachment-location)

### 插件作用
- 修改附件文件夹位置
- 修改粘贴的文件名

### 📌 设置指南

#### 1. 设置图片保存路径（location for new attachment）

将粘贴图片的路径设置为：`assets/${filepath}`

例如：如果你的笔记路径是 `study/note.md`，  
那么图片保存目录应为：`assets/study/note.md/`

---

#### 2. 设置图片名称（generated file name）

将粘贴图片的默认命名规则设置为：`${filename}`

这会自动使用笔记文件名作为图片文件名。

---

#### 3. 启用自动清理（should delete orphan attachment）

✅ **开启该选项**：  
当你删除某个笔记时，自动删除该笔记对应的图片资源，保持项目整洁。

---

### ✅ 效果示意

| 选项     | 示例设置                    | 说明          |
| ------ | ----------------------- | ----------- |
| 图片路径   | `assets/study/note.md/` | 与笔记路径一致     |
| 图片文件名  | `note`                  | 与笔记文件名一致    |
| 删除无用附件 | ✅ 开启                    | 删除笔记时自动清理附件 |
