```bash
# 初始化仓库
mkdir learning-notes
cd learning-notes
git init

# 使用 Typora 创建笔记
touch "Markdown 语法.md"
touch "Git 使用指南.md"

# Git 提交
git add .
git commit -m "首次提交，添加 Markdown 和 Git 笔记"

# 推送到 GitHub
git remote add origin https://github.com/yourname/learning-notes.git
git push -u origin master
```

sas