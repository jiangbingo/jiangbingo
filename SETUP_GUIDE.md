# GitHub Profile README 设置指南

## 📋 前置条件

你需要创建一个与你的 GitHub 用户名同名的特殊仓库：`jiangbingo/jiangbingo`

## 🚀 快速开始

### 1. 创建 GitHub 仓库

1. 访问 https://github.com/new
2. 仓库名称填写：`jiangbingo`（必须与你的用户名完全一致）
3. 设置为 **Public** 公开仓库
4. **不要**勾选 "Add a README file"（我们已经有自己的了）
5. 点击 "Create repository"

### 2. 上传 README.md

创建仓库后，有几种方式上传：

#### 方式一：直接在网页上编辑（推荐）

1. 在新创建的仓库中，点击 "creating a new file"
2. 文件名填写：`README.md`
3. 将本目录下的 `README.md` 内容复制粘贴进去
4. 滚动到页面底部，填写 commit 信息
5. 点击 "Commit new file"

#### 方式二：通过 Git 命令行

```bash
# 初始化仓库
cd jiangbingo-github-profile
git init

# 添加远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/jiangbingo/jiangbingo.git

# 添加并提交文件
git add README.md
git commit -m "Initial commit: GitHub Profile README"

# 推送到 GitHub
git branch -M main
git push -u origin main
```

## 🎨 自定义配置

### 更新用户名

在 README.md 中将所有 `jiangbingo` 替换为你的实际 GitHub 用户名：

```markdown
# 找到这些位置并替换：
- https://github-readme-stats.vercel.app/api?username=jiangbingo
- https://komarev.com/ghpvc/?username=jiangbingo
```

### 更新联系方式

找到并更新这些部分：

```markdown
## 📫 **联系方式**
[![Email](https://img.shields.io/badge/📧_Email-联系我-red?style=for-the-badge&logo=gmail)](mailto:your-email@example.com)
[![LinkedIn](https://img.shields.io/badge/🔗_LinkedIn-连接我-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/yourprofile)
```

替换为你的真实邮箱和 LinkedIn 链接。

### 更新技能和技术栈

根据你的实际技能调整：

```markdown
## 🔥 **技术栈徽章**
## 🏆 **精选项目**
## 🔭 **当前关注与正在建设**
```

## 🌟 固定仓库（Pinned Repositories）

让你的项目在主页更显眼：

1. 访问你的 GitHub 主页
2. 点击 "Customize your pins"
3. 选择最多 6 个仓库进行固定
4. 拖拽调整显示顺序

## 📊 动态组件说明

本 README 使用的动态组件：

| 组件 | 功能 | 来源 |
|------|------|------|
| GitHub Stats | 显示提交数、Star、Fork 等 | [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| Top Languages | 显示最常用的编程语言 | [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| GitHub Streak | 显示连续贡献天数 | [github-readme-streak-stats](https://github.com/Ashutosh00710/github-readme-streak-stats) |
| Activity Graph | 显示贡献活动图表 | [github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) |
| Profile Views | 显示主页访问次数 | [profile-view-counter](https://github.com/antonkomarev/github-profile-views-counter) |

## 🎨 主题自定义

### 主题颜色

当前使用 `radical` 主题，可选主题：
- `default`, `dim`, `dracula`, `radical`, `merko`, `tokyonight`, `onedark`, `cobalt`, `synthwave`

修改方式：
```markdown
# 将 theme=radical 改为你喜欢的主题
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jiangbingo&theme=dracula)
```

### 颜色自定义

也可以自定义颜色：
```markdown
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jiangbingo&bg_color=0D1117&title_color=7F5AF0&icon_color=7F5AF0&text_color=FFFFF0)
```

## 🔄 保持更新

### 自动更新最新博客文章

如果你有博客，可以添加 RSS 自动更新：

```markdown
<!-- 使用 rss-to-json 或类似服务 -->
### 📝 最新博客
[![RSS](https://img.shields.io/badge/RSS-订阅-orange)](https://your-blog.com/rss.xml)
```

### WakaTime 编码时间统计

1. 注册 [WakaTime](https://wakatime.com/)
2. 安装 WakaTime 插件到你的 IDE
3. 在 README 中添加：

```markdown
![WakaTime](https://github-readme-stats.waka.dev/v1/jiangbingo?theme=radical)
```

## 📚 参考资源

- [GitHub Profile README 指南](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [GitHub Readme Stats 文档](https://github.com/anuraghazra/github-readme-stats)

## 🎉 完成！

设置完成后，访问 `https://github.com/jiangbingo` 即可看到你的新主页！

---

有问题？欢迎访问我的个人网站：[jiangbingo.github.io](https://jiangbingo.github.io)
