# 审稿回复准备与数据处理分析项目结构

```
review_responser/
├── data/                           # 数据目录
│   ├── input/                      # 输入数据
│   │   ├── review_comments/        # 审稿意见文件
│   │   ├── manuscripts/           # 论文原文件
│   │   └── metadata/              # 元数据文件
│   ├── processed/                  # 处理后的数据
│   │   ├── extracted_comments/     # 提取的审稿意见
│   │   ├── analyzed_content/       # 分析的论文内容
│   │   └── response_templates/     # 回复模板
│   └── output/                     # 输出结果
│       ├── responses/              # 生成的回复
│       ├── statistics/             # 统计数据
│       └── reports/                # 分析报告
├── prompts/                        # 提示词目录
│   ├── extraction/                 # 信息提取提示词
│   ├── analysis/                   # 分析提示词
│   ├── generation/                 # 生成提示词
│   └── templates/                  # 模板提示词
├── workflows/                      # 工作流定义
│   ├── review_processing/          # 审稿处理流程
│   ├── response_generation/        # 回复生成流程
│   └── data_analysis/              # 数据分析流程
├── analysis/                       # 分析模块
│   ├── comment_analyzer/           # 评论分析器
│   ├── content_extractor/          # 内容提取器
│   └── statistics_generator/       # 统计生成器
├── reports/                        # 报告模板
│   ├── html/                       # HTML报告模板
│   ├── markdown/                   # Markdown报告模板
│   └── json/                       # JSON报告模板
├── config/                         # 配置文件
│   ├── settings.json               # 主配置文件
│   ├── templates.json              # 模板配置
│   └── rules.json                  # 处理规则
└── docs/                           # 文档目录
    ├── usage_guide.md              # 使用指南
    ├── api_reference.md            # API参考
    └── examples/                   # 示例文件
```

## 核心功能模块

### 1. 数据输入处理
- **审稿意见解析**：提取审稿人意见、建议、问题
- **论文内容分析**：提取关键信息、结构、论点
- **元数据处理**：处理作者信息、期刊要求等

### 2. 智能回复生成
- **分类回复**：根据意见类型生成不同回复
- **个性化定制**：基于论文内容定制回复
- **模板匹配**：使用预定义模板快速生成

### 3. 数据分析统计
- **审稿意见统计**：意见类型分布、严重程度分析
- **回复质量评估**：回复完整性、准确性评估
- **流程效率分析**：处理时间、改进建议

### 4. 报告生成
- **综合报告**：包含所有分析和建议的完整报告
- **分项报告**：针对特定方面的详细报告
- **可视化图表**：数据可视化展示