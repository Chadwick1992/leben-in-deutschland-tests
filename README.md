# Leben in Deutschland Trainer

**English** | [中文](#中文)

A single-file web app for practising the German citizenship test (*Einbürgerungstest*, "Leben in Deutschland"). No installation and no server: open `index.html` in a browser, or publish it with GitHub Pages.

## Basic information

| | |
|---|---|
| Authors | Changjiang Yi and Claude (Anthropic) |
| Version | 1.0 (November 2026) |
| Question set | 460 questions: 300 general + 10 for each of the 16 states |
| Real test format | 33 questions (30 general + 3 state), 60 minutes, 17 correct to pass |
| Languages | German questions; interface language: Chinese / English; question help language: Chinese / English / none |
| Tech | One HTML file, plain JavaScript, data in the browser (localStorage) |
| Status | Unofficial practice tool, not affiliated with BAMF |

## Features

- **Mock exam:** choose a state, get 30 general + 3 state questions and a 60-minute timer. From the second run on you are asked whether to include questions you have seen before.
- **Question bank:** all 460 questions with search, state filter and answers.
- **Wrong-answer book:** wrong or skipped questions are collected automatically; build an exam from them. Two correct answers in a row mark a question as mastered.
- **History:** score, pass/fail, time used, date and time of every session, total training time and a trend chart. Export / import a backup as JSON.
- **Two language switches:** interface language (中文 / English) and question help language (中文 / English / none).
- **Mobile friendly.**

## Use

Open `index.html`. To host it online: create a **public** repository, upload this file, then *Settings → Pages → Deploy from a branch → `main` / root*.

Results are stored in the browser you use. To sync phone and computer, connect your own GitHub under History → Cloud sync (a private Gist, token with `gist` scope only, kept in that browser). Export/import JSON remains as a manual backup.

## Notes

The German questions come from the official catalogue; the answer key was proofread by the authors. If you find a mistake, please check it against the official BAMF catalogue.

---

## 中文

用来练习德国入籍考试（Leben in Deutschland）的单文件网页应用。不需要安装，也不需要服务器：用浏览器打开 `index.html` 就能用，也可以用 GitHub Pages 发布。

## 基本信息

| | |
|---|---|
| 创作人 | Changjiang Yi 和 Claude（Anthropic） |
| 版本 | 1.0（2026 年 11 月） |
| 题库 | 460 题：300 道通用题加 16 个州各 10 道 |
| 正式考试格式 | 33 题（30 道通用题加 3 道州题），60 分钟，答对 17 题及格 |
| 语言 | 题目为德语；界面语言可选中文或 English，题目辅助语言可选中文、English 或无 |
| 技术 | 一个 HTML 文件，原生 JavaScript，数据保存在浏览器（localStorage） |
| 性质 | 非官方练习工具，与 BAMF 无关联 |

## 功能

- **模拟考试：** 选择一个州，生成 30 道通用题加 3 道州题，60 分钟倒计时。从第二次生成起，会询问是否包含以前出现过的题目。
- **题库：** 全部 460 题，可搜索、按州筛选、查看答案。
- **错题本：** 答错或没答的题自动收集，可以用错题生成试卷。同一题连续答对 2 次标为“已掌握”。
- **成绩记录：** 每次的得分、是否及格、用时、开始日期和时间，累计训练时间和走势图。可导出和导入 JSON 备份。
- **两个语言开关：** 界面语言（中文 / English）和题目辅助语言（中文 / English / 无）。
- **适配手机浏览器。**

## 使用

打开 `index.html` 即可。想放到网上：新建一个**公开**仓库，上传这个文件，然后在 *Settings → Pages → Deploy from a branch → `main` / root* 里开启。

成绩保存在你使用的浏览器里。要让手机和电脑同步，请在“成绩记录 → 云端同步”里连接你自己的 GitHub（私有 Gist，令牌只需 gist 权限，仅保存在该浏览器）。导出/导入 JSON 仍可作为手动备份。

## 说明

德语题目来自官方题库，答案经作者校对。如果发现错误，请对照 BAMF 官方题库核实。
