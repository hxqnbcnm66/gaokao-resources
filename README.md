# 高考资源索引

这个仓库用来记录有用的高考资源仓库，方便以后出卷子时快速找到题目。

## 资源仓库

### 1. rainewhk/gaokao
- **仓库地址**: https://github.com/rainewhk/gaokao
- **内容**: 2010-2024年高考试题数据（JSON格式）
- **科目**: 物理、数学、化学、生物、语文、英语、历史、地理、政治
- **数据格式**: JSONL，按年份/科目/题型组织
- **使用方法**:
  ```bash
  git clone https://github.com/rainewhk/gaokao.git
  # 数据在 dataset/科目/年份/试卷类型/题型.jsonl
  ```
- **优点**: 数据完整，覆盖年份多，有答案和解析
- **缺点**: 没有图，只有文字

### 2. open-compass/GAOKAO-Eval
- **仓库地址**: https://github.com/open-compass/GAOKAO-Eval
- **内容**: 2024年新课标I卷（江西用的卷子）的题目
- **科目**: 物理、数学等
- **数据格式**: Jupyter Notebook（.ipynb）
- **使用方法**: 直接查看notebook文件
- **优点**: 有答案和解析，格式清晰
- **缺点**: 只有2024年一卷

## 使用方法

### 方法1：直接克隆仓库
```bash
git clone https://github.com/rainewhk/gaokao.git
```

### 方法2：让AI直接出卷
- 告诉AI科目和年份，AI直接从这些仓库里找题目
- AI可以生成Word/PDF格式的试卷

## 注意事项

- 这些仓库的数据都是文字版，没有图
- 出卷时需要AI根据文字描述生成图（SVG或截图）
- 数据持续更新中，建议定期拉取最新版本

## 更新记录

- 2026-07-03: 初始化仓库，添加 rainewhk/gaokao 和 open-compass/GAOKAO-Eval
