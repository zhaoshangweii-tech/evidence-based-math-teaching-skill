# Evidence-Based Math Teaching Skill

面向小学数学教师、教研员和课程研发者的证据型教研 Skill。

它把一次教学研究任务组织成完整链路：

`官方资料检索 → 课标教材分析 → 学情证据编码 → 教学设计 → 可编辑成果 → 质量验收`

## 适用场景

- 课标与教材解读
- 不同教材版本横向比较
- 学段纵向衔接分析
- 学情前测与学生作答分析
- 单元说课、课时说课和教学设计
- 可编辑PPT、逐页话术和说课逐字稿
- 教研成果的数据、来源和版面复核

不适合普通作业答题、只需要一个知识结论的简单问答。

## 核心特点

### 1. 官方证据优先

优先使用课程标准、国家或省级教材平台、出版社教材和教师用书。明确教材版本、检索日期、印刷页码与平台资源页，不把网络课例误写成教材正式课题。

### 2. 区分事实、观察与推断

每个重要结论都尽量回溯到原课页、学生样本、数量或数据明细。对模糊作答采用保守判读，不根据一条二维线条强行推断学生的三维意图。

### 3. 从学情证据推导教学

按照以下链路组织教学论证：

`课标要求 → 教材定位 → 学生起点 → 学习困难 → 教学目标 → 核心活动 → 学习支持 → 评价证据`

### 4. 交付可直接使用的成果

当用户需要正式成果时，不停留在建议或提纲，而是生成可编辑课件、PDF预览、逐字稿、数据明细、来源索引和验证记录。

## 安装

### 项目级安装

将 Skill 目录复制到项目中：

```bash
mkdir -p .trae/skills
cp -R skills/evidence-based-math-teaching .trae/skills/
```

### TRAE CN 全局安装

```bash
mkdir -p ~/.trae-cn/skills
cp -R skills/evidence-based-math-teaching ~/.trae-cn/skills/
```

### TRAE International 全局安装

```bash
mkdir -p ~/.trae/skills
cp -R skills/evidence-based-math-teaching ~/.trae/skills/
```

重新打开会话后，即可在匹配的教学教研任务中自动触发。

## 示例请求

```text
围绕指定数学主题，对国家中小学智慧教育平台现行教材进行横向比较，
找出相关内容，并说明不同版本的培养策略。
```

```text
分析这批学情前测。先建立可观察的判读标准，
逐份编码，再提炼学生起点、典型迷思和教学回应。
```

```text
根据课标、教材比较和学情数据生成一份可编辑说课PPT，
每页写入备注，并提供PDF预览、逐字稿和验证记录。
```

## 目录

```text
skills/evidence-based-math-teaching/
├── SKILL.md
└── references/
    ├── deliverable-quality.md
    ├── evidence-workflow.md
    ├── learning-evidence-analysis.md
    ├── output-templates.md
    └── textbook-analysis.md
```

## 设计原则

- 不保存教师或学生的个人信息。
- 不发布未经授权的学生原始作答。
- 不把推断写成事实。
- 不把“最新版”当作自然年份标签。
- 不追求形式上的复杂，而追求证据可追溯、结论可解释、成果可复用。

## License

MIT
