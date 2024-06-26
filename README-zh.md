# RSS-GPT

[![](https://img.shields.io/github/actions/workflow/status/yinan-c/RSS-GPT/cron-job.yml?label=cron-job)](https://github.com/yinan-c/RSS-GPT/actions/workflows/cron_job.yml)
[![](https://img.shields.io/github/actions/workflow/status/yinan-c/RSS-GPT/jekyll-gh-pages.yml?label=GitHub%20Pages)](https://github.com/yinan-c/RSS-GPT/actions/workflow/jekyll-gh-pages.yml)

[中文教程](https://yinan.me/rss-gpt-manual-zh.html) | [中文介绍](https://yinan.me/rss-gpt.html) | [README](README.md)

## 功能

- 在 GitHub 仓库和 GitHub Pages 上自托管 RSS 订阅源。

- 使用 ChatGPT 来总结 RSS 订阅源。

- 聚合多个 RSS 订阅源。

- 为 RSS 订阅源添加基于标题，内容，URL 的关键词过滤器。

## 配置

- Fork 这个仓库

- 添加仓库 Secrets

    - U_NAME: 你的 GitHub 用户名

    - U_EMAIL: 你的 GitHub 邮箱

    - WORK_TOKEN: 你的GitHub个人访问令牌,需要有 `repo` 和 `workflow` 权限

    - OPENAI_API_KEY: 你的 OpenAI API 密钥,在[这里](https://platform.openai.com/account/api-keys)获取

- 在仓库设置中启用 GitHub Actions 部署 GitHub Pages

- 在 `config.ini` 中配置你的RSS订阅源

- 把 `main.py` 中的链接改成你自己的 GitHub Pages 链接。

也可以参考更详细的[中文教程](https://yinan.me/rss-gpt-manual-zh.html)。

本项目有自托管的订阅源在我的 [GitHub Pages](https://yinan.me/RSS-GPT/rss/) 以及 在本项目 rss/ 文件夹内，欢迎订阅。
如果有任何问题或有关于 rss feeds 的建议，欢迎邮件联系我。
如果你觉得本项目有帮助，欢迎 star。
