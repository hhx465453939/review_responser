# 技术澄清与误解处理提示词

## 核心理念：基于"已有证据澄清误解"的策略

### 🎯 主要应用场景

1. **审稿人误认为缺失已存在的内容**
2. **对方法学透明度的误解**
3. **对技术验证充分性的质疑**
4. **对结果展示方式的关切**

## 📋 技术澄清标准流程

### 1. 误解识别
**识别关键词**：
- "not clearly reported" - 实际已报告但展示不够
- "should be presented more transparently" - 透明度问题非缺失问题
- "mentioned but should be..." - 已有但需要强调
- "lacks evidence" - 可能已有证据但未突出

### 2. 证据定位
**查找现有内容**：
- 搜索正文中的相关描述
- 检查补充材料中的详细信息
- 定位具体的图表和数据
- 找到方法学描述

### 3. 澄清回应结构
```markdown
### Comment X: [技术澄清标题]
**Reviewer's Concern**: "[原文引用]"

**Our Response**: We thank the reviewer for bringing this to our attention. To clarify, our study actually includes [具体已有内容描述].

[详细证据展示]:
- [具体证据1，包含位置引用]
- [具体证据2，包含位置引用]

**Revisions Made**: **For improved transparency, we have now [具体展示改进] in Section X.X, paragraph Y.**
```

## 🔍 常见技术澄清场景及处理策略

### 场景1：性能指标"缺失"问题
**典型表述**："performance metrics are not clearly reported"
**澄清策略**：
1. 明确指出已有的验证内容
2. 提供补充材料中的具体位置
3. 承诺在正文中增加展示

**回复模板**：
```
To clarify, our study includes extensive validation: [列举已有验证]
For improved transparency, we have now explicitly reported these metrics in the main text.
```

### 场景2：方法学透明度质疑
**典型表述**："methodology should be more transparent"
**澄清策略**：
1. 详细说明已有的方法学描述
2. 指出具体的方法学章节
3. 强调已有的技术细节

**回复模板**：
```
We appreciate the concern about methodological transparency. Our study provides detailed methodology in Section 2.X, including [具体内容].
```

### 场景3：验证不充分的误解
**典型表述**："validation is insufficient"
**澄清策略**：
1. 列举已完成的验证实验
2. 指出验证结果的位置
3. 强调验证的充分性

**回复模板**：
```
We thank the reviewer for this concern. Our validation includes: [列举验证内容]
These comprehensive validations are presented in [具体位置].
```

## ⚠️ 技术澄清注意事项

### 避免防御性语言
- ❌ "We completely disagree with this assessment"
- ✅ "To clarify, our study actually includes..."

### 保持专业平等
- ❌ "We sincerely apologize for the confusion"  
- ✅ "We thank the reviewer for bringing this to our attention"

### 重点突出已有成果
- 明确指出已完成的工作
- 提供具体的证据位置
- 强调研究的完整性

## 💡 成功案例参考

### DNN性能指标澄清案例
**审稿人误解**："性能指标在正文中没有明确报告"
**实际情况**：已有完整的混淆矩阵和准确率数据
**澄清策略**：
1. 明确列出已有的验证内容
2. 指出补充材料的具体位置
3. 承诺在正文中增加展示

**效果评估**：
- ✅ 澄清了技术误解
- ✅ 避免了不必要的重复工作
- ✅ 保持了研究完整性
