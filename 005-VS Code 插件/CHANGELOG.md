更新日志
===

## 【0.0.8】2020-05-09 16:25:50

* [x] 添加了类型转换功能，快捷键 `Command/Ctrl + Shift + J`，转换顺序：`text_style -> textStyle -> TextStyle -> TEXT_STYLE -> text-style`

## 【0.0.8】2020-05-09 15:00:44

* [x] 添加联系方式
* [x] 修复模板内容

## 【0.0.7】2020-05-08 10:56:55

* [x] 修复无法打开隐藏了 `.js` 或者 `.jsx` 路径的内容，例如：`import Table2 from '../obj/Table2'`（Table2.jsx） 以及 `import store from '../../temp'`（temp.js）。

## 【0.0.6】2020-05-07 08:11:19

* [x] 添加 LeetCode 的文章模板

## 【0.0.5】2020-05-06 17:16:45

* [x] 修复 `src` 目录打开问题：当前找到最近的 `src` 进行跳转

## 【0.0.4】2020-05-06 14:16:40

* [x] Markdown 模板自动生成：

1. `template`：jsliang 的文章模板
2. `time`：jsliang 的时间注释
3. `category`：jsliang 的目录生成
4. `ads`：jsliang 的广告 + 文档声明

## 【0.0.3】2020-05-05 15:37:14

* [x] 在 JSX 文件中通过 `import ... from ...` 导入的 CSS，支持通过 `Ctrl/Command + 点击` 跳转到对应文件中。
* [x] 在 JSX 文件中通过 `import ... from 'src/...'` 形式导入的内容，支持 `Ctrl/Command + 点击` 跳转到对应文件中。（注意，是项目根路径下存在 `src` 文件夹）

## 【0.0.2】2020-4-30 16:31:07

* [x] 提供 `@api` 快速插入 `snippets` 代码片段
* [x] 提供 `!!` 快速生成 H5 常用文件代码
* [x] 提供 `Ctrl/Command + Shift + I` 快速插入函数注释（JS Doc）

## 【0.0.1】2020-4-30 15:18:38

* [x] 初始化插件

console.log('');
