
# 保持Kaggle Notebook活跃 - Tampermonkey脚本

## 描述

这个Tampermonkey脚本旨在通过模拟用户操作来保持Kaggle Notebook的会话活跃。脚本会自动点击Kaggle Notebook界面中的按钮，以随机间隔添加、运行和删除单元格，防止会话因长时间不活动而超时。

## 功能

- **模拟用户操作**：脚本会模拟点击Kaggle Notebook中的“添加单元格”、“运行当前单元格”和“删除单元格”按钮，确保会话保持活跃。
- **随机间隔**：脚本随机生成几分钟的间隔（可自定义），以模仿自然的用户交互，降低被检测为自动化的风险。
- **自动循环**：脚本会在后台持续运行，每次间隔结束后自动触发自身。

## 安装

1. **安装Tampermonkey**：确保你已在浏览器中安装了Tampermonkey扩展。你可以从[这里](https://www.tampermonkey.net/)下载。
2. **安装脚本**：点击[这里](https://greasyfork.org/zh-CN/scripts/504382-keep-kaggle-notebook-alive)打开脚本页面，点击“安装此脚本”按钮。

## 使用方法

1. **打开Kaggle Notebook**：访问[Kaggle](https://www.kaggle.com/)上的任意Notebook。
2. **脚本自动执行**：脚本会自动启动，保持你的Notebook会话活跃。
3. **监控控制台**：你可以打开浏览器的开发者控制台（按F12）查看脚本日志并监控其操作。

## 配置

- **间隔设置**：脚本配置为每几分钟随机触发操作。你可以通过调整脚本中的`Math.random()`函数参数来修改这个范围。

## 注意事项

- **免责声明**：此脚本旨在个人使用，以防止在活跃工作期间Kaggle Notebook会话超时。请合理使用。

## 许可

此项目使用MIT许可证进行许可。
