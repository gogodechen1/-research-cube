# Gamma风格设计指南 - 聚研AI系统

本文档提供了基于Gamma设计语言的聚研AI系统界面设计指南，旨在确保整个系统视觉和交互体验的一致性、专业性和现代感。

## 1. 设计原则

### 1.1 简洁清晰

- 减少视觉噪音，优先展示关键信息
- 使用充足的留白创造呼吸感
- 内容分层明确，视觉层次清晰

### 1.2 专业可靠

- 运用稳重的配色方案传达专业感
- 数据可视化精准、易读
- 使用高质量的图标和插图

### 1.3 现代友好

- 界面元素运用适度圆角
- 恰当使用阴影和渐变增添深度
- 交互反馈及时、明确、愉悦

### 1.4 一致统一

- 在整个系统中保持视觉语言一致
- 交互模式和导航逻辑统一
- 术语和提示文案风格统一

## 2. 颜色系统

![颜色系统](img/color-system.svg)

### 2.1 主色调

- **主要蓝色** - `#1a5fb4`
  - 用于主要按钮、强调元素、主标题
  - 深色变体: `#15417e`
  - 浅色变体: `#3584e4`

- **辅助橙色** - `#ff7800`
  - 用于突出重要信息、提示、强调按钮
  - 深色变体: `#cc6000`
  - 浅色变体: `#ff9433`

### 2.2 中性色

- **深灰** - `#333333` (正文文本)
- **中灰** - `#666666` (次要文本)
- **浅灰** - `#999999` (提示文本)
- **超浅灰** - `#f8f9fa` (背景色)
- **纯白** - `#ffffff` (卡片背景)

### 2.3 功能色

- **成功绿** - `#2ec27e` (成功状态、完成)
- **警告黄** - `#f5c211` (警告状态、注意)
- **错误红** - `#e01b24` (错误状态、删除)
- **信息蓝** - `#3584e4` (信息提示、详情)

### 2.4 颜色应用规则

- 大面积使用中性色
- 强调和引导使用主色调
- 功能色仅用于表示状态和结果
- 保持良好的色彩对比度，确保可访问性

## 3. 排版系统

### 3.1 字体

- **主要字体**: Noto Sans SC
- **辅助字体**: 系统无衬线字体(fallback)

### 3.2 字号体系

- **大标题**: 28-32px, 700粗细
- **中标题**: 22-24px, 700粗细
- **小标题**: 18-20px, 700粗细
- **正文**: 15-16px, 400粗细
- **小字**: 13-14px, 400粗细
- **超小字**: 12px, 400粗细

### 3.3 行高与间距

- 标题行高: 1.2-1.3
- 正文行高: 1.5-1.6
- 段落间距: 1.5em
- 标题与正文间距: 0.75em

### 3.4 文本对齐

- 标题居左对齐
- 大段文本左对齐
- 短文本与数字可居中
- 避免大段两端对齐

## 4. 组件样式

### 4.1 按钮

![按钮样式](img/button-styles.svg)

- **主要按钮**:
  - 背景色: 主蓝 `#1a5fb4`
  - 文本色: 白色
  - 圆角: 8px
  - 内边距: 12px 24px
  - hover状态: 深蓝 `#15417e`

- **次要按钮**:
  - 背景色: 白色
  - 边框: 1px solid `#d5d5d5`
  - 文本色: 深灰 `#333333`
  - 圆角: 8px
  - 内边距: 12px 24px
  - hover状态: 背景色 `#f8f9fa`

- **危险按钮**:
  - 背景色: 错误红 `#e01b24`
  - 文本色: 白色
  - 圆角: 8px
  - 内边距: 12px 24px
  - hover状态: 深红色

### 4.2 表单控件

- **输入框**:
  - 高度: 40px
  - 边框: 1px solid `#d5d5d5`
  - 内边距: 8px 12px
  - 圆角: 6px
  - 获焦效果: 蓝色边框阴影

- **复选框/单选框**:
  - 尺寸: 18px × 18px
  - 选中色: 主蓝 `#1a5fb4`

- **下拉菜单**:
  - 样式与输入框一致
  - 下拉图标使用Font Awesome

### 4.3 卡片

- **标准卡片**:
  - 背景色: 白色
  - 圆角: 8px
  - 阴影: 0 4px 12px rgba(0,0,0,0.05)
  - 内边距: 24px
  - 间距: 20px

- **边框卡片**:
  - 背景色: 白色
  - 圆角: 8px
  - 边框: 1px solid `#e0e0e0`
  - 内边距: 24px
  - 间距: 20px

### 4.4 导航元素

- **顶部导航**:
  - 高度: 64px
  - 背景色: 白色
  - 阴影: 0 2px 8px rgba(0,0,0,0.05)

- **侧边导航**:
  - 宽度: 240px
  - 背景色: 白色或超浅灰
  - 激活状态: 左侧蓝色条+浅蓝背景

- **面包屑**:
  - 字号: 14px
  - 颜色: 中灰色
  - 当前项加粗或蓝色

## 5. 图表与数据可视化

![图表样式](img/chart-styles.svg)

### 5.1 配色方案

- **饼图/环形图**: 使用渐变蓝色系
- **柱状图/条形图**: 单色图表使用主蓝，多数据使用彩色区分
- **折线图**: 使用蓝色或多色线条，淡色填充区域

### 5.2 样式规范

- 网格线使用浅灰色(#e0e0e0)，细线
- 轴标签使用中灰色(#666666)
- 图例清晰，字体大小12px
- 数据标签使用中灰或深灰，确保可读性
- 图表添加适当动画效果增强交互体验

## 6. 图标系统

### 6.1 图标风格

- 优先使用**线性图标**
- 主要采用Font Awesome图标库
- 统一线条粗细(1.5-2px)
- 图标颜色与周围文本保持一致

### 6.2 图标尺寸

- 导航图标: 20-24px
- 功能按钮图标: 16-20px
- 状态指示图标: 14-16px
- 辅助装饰图标: 12-14px

## 7. 间距与网格

### 7.1 基础间距

- 4px基础网格
- 内容间距使用8px的倍数:
  - 紧凑间距: 8px
  - 标准间距: 16px
  - 宽松间距: 24px
  - 分区间距: 32-48px

### 7.2 页面布局

- 内容区最大宽度: 1200px
- 侧边栏固定宽度: 240px
- 栅格系统: 12列
- 列间距: 24px
- 外边距: 24px以上

## 8. 动效指南

### 8.1 基础过渡效果

- 按钮悬停: 200ms ease-out
- 内容淡入: 300ms ease-out
- 菜单展开: 250ms ease

### 8.2 加载状态

- 使用简洁的spinner或进度条
- 长任务使用百分比进度指示
- 动效应保持轻量，避免过于花哨

### 8.3 页面转场

- 页面切换使用淡入淡出
- 模态框使用缩放+淡入组合
- 列表项使用级联动画效果

## 9. 使用Gamma样式组件示例

为使界面风格与Gamma文档一致，可参考以下实现方式：

### 9.1 主页内容布局

```html
<div class="gamma-section">
  <h1 class="gamma-heading">物流运输技术研究</h1>
  <div class="gamma-two-column">
    <div class="gamma-card">
      <h2>专利分布</h2>
      <div class="chart-container">
        <!-- 图表内容 -->
      </div>
    </div>
    <div class="gamma-card">
      <h2>技术趋势</h2>
      <ul class="gamma-list">
        <li>自动驾驶技术应用增长32%</li>
        <li>绿色能源解决方案占比提升</li>
        <li>物联网技术融合加速发展</li>
      </ul>
    </div>
  </div>
</div>
```

### 9.2 数据卡片样式

```html
<div class="gamma-metrics-row">
  <div class="gamma-metric-card">
    <div class="metric-icon">
      <i class="fas fa-file-alt"></i>
    </div>
    <div class="metric-value">2,387</div>
    <div class="metric-label">专利总数</div>
    <div class="metric-change positive">+12.5%</div>
  </div>
  <!-- 更多指标卡片 -->
</div>
```

## 10. 参考资源

- [Gamma文档示例](https://gamma.app/docs/2025-68zoaswmvwi5fqz?mode=doc)
- [Font Awesome图标库](https://fontawesome.com/)
- [Google Fonts - Noto Sans SC](https://fonts.google.com/specimen/Noto+Sans+SC)
- [ApexCharts图表库](https://apexcharts.com/)

---

通过遵循本指南的设计原则和具体规范，聚研AI系统的界面将具有与Gamma文档一致的专业、现代和用户友好的视觉体验。 