# Voxel 设计规范

Voxel 是一个模仿 Minecraft 风格的设计规范，主要用于创建游戏和应用程序的用户界面。本文档提供了一些基本的设计原则和指南，可以帮助开发人员快速创建符合 Voxel 规范的用户界面。

If you are a non-native Chinese speaker, please [click here](i18n.md).

## 基本原则

- **简洁性**：Voxel 设计规范强调简洁清晰，避免过多的视觉噪音。
- **一致性**：所有组件的设计都应该保持一致性，遵循相同的颜色、字体、间距等规则。
- **可访问性**：Voxel 应该易于使用，并且应该考虑到所有用户的不同需求和能力。
- **灵活性**：Voxel 应该是可定制的，以便开发人员可以根据自己的需要进行修改和扩展。

## 颜色规范

Voxel 的颜色方案采用了明亮的基调，突出了简约和清晰的特点。以下是 Voxel 的颜色规范：

- **主要颜色**：#7DBFEB
- **辅助颜色**：#F5A623，#4A90E2，#50E3C2，#B8E986
- **背景颜色**：#FFFFFF
- **文本颜色**：#000000，#666666

## 字体规范

Voxel 采用了简约的字体设计，以保证良好的可读性。以下是 Voxel 的字体规范：

- **标题字体**：Segoe UI Bold
- **正文字体**：Segoe UI Regular
- **字体大小**：标题字体为 24pt，正文字体为 14pt

## 组件规范

### 按钮

Voxel 的按钮设计应该简洁明了，醒目易于点击。以下是 Voxel 的按钮规范：

- **背景颜色**：#7DBFEB
- **文本颜色**：#FFFFFF
- **状态变化**：当鼠标悬停在按钮上时，按钮会变成辅助颜色，当鼠标按下时，按钮会变暗。

```
<button class="voxel-button">按钮</button>
```

### 输入框

Voxel 的输入框设计应该简单易用，能够清晰地显示用户输入的内容。以下是 Voxel 的输入框规范：

- **背景颜色**：#FFFFFF
- **文本颜色**：#000000
- **边框颜色**：#7DBFEB
- **状态变化**：当输入框获取焦点时，边框颜色会变成辅助颜色。

```
<input type="text" class="voxel-input" placeholder="请输入内容">
```

### 复选框和单选框

Voxel 的复选框和单选框设计应该清晰易用，能够准确地显示用户所选择的选项。以下是 Voxel 的复选框和单选框规范：

- **背景颜色**：#FFFFFF
- **文本颜色**：#000000
- **边框颜色**：#7DBFEB
- **状态变化**：当复选框或单选框被选中时，背景颜色会变成主要颜色。

```
<input type="checkbox" class="voxel-checkbox" id="checkbox1">
<label for="checkbox1">选项1</label>

<input type="radio" class="voxel-radio" id="radio1" name="radio">
<label for="radio1">选项1</label>
```

### 下拉菜单

Voxel 的下拉菜单设计应该简单明了，易于使用和理解。以下是 Voxel 的下拉菜单规范：

- **背景颜色**：#FFFFFF
- **文本颜色**：#000000
- **边框颜色**：#7DBFEB
- **状态变化**：当下拉菜单被打开时，背景颜色会变成辅助颜色。

```
<select class="voxel-select">
  <option>选项1</option>
  <option>选项2</option>
  <option>选项3</option>
</select>
```

### 卡片

Voxel 的卡片设计应该简洁明了，能够清晰地显示卡片中的内容。以下是 Voxel 的卡片规范：

- **背景颜色**：#FFFFFF
- **文本颜色**：#000000
- **边框颜色**：#7DBFEB
- **圆角**：4px

```
<div class="voxel-card">
  <div class="voxel-card-header">
    标题
  </div>
  <div class="voxel-card-body">
    内容
  </div>
</div>
```

## 总结

Voxel 是一个简约明了的设计规范，可以帮助开发人员快速创建符合 Minecraft 风格的用户界面。通过遵循 Voxel 的基本原则和指南，开发人员可以轻松地创建出易于使用和定制的用户界面。

