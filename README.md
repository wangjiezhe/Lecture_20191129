# Lecture for video course on Nov 29, 2019

## 一些笔记

### 切换字体

```tex
\setCJKsansfont{Source Han Sans SC}
\usepackage{fourier}
```

### 调整行间距

```tex
\usepackage{setspace}
\setstretch{1.3}
```

### 底部与标题页显示日期不同

```tex
\date[Nov 2019]{2019年11月29日}
```

### 试卷类型

使用 `exam` 类：

```tex
\documentclass[a4paper]{exam}
```

自动调整空档：

```tex
\vspace*{\stretch{1}}
```

