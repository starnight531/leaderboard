# 依赖项：
- 下载npm工具后使用npm将react-scripts下载到当前目录下：

  ```bash
  npm install react-scripts
  ```
- 也可以下载到全局：

  ```bash
  npm -g install react-scripts
  ```

- 由于上传到github已经是html文件，所以该依赖项加入了.gitignore

# 构建：

- 在项目总目录下运行

  ```bash
  npm run build
  ```
- 构建好的网页是build目录下的 index.html & leaderboard.html
  可能遇到mv重命名结果多空格情况，在文件夹下删除空格即可

# 细节：
- 网站数据在 src/mocks 下，每个json文件对应一个网页
- 网页样式在 src/index.tsx 下，分出六个标签都在leaderboardLib.tsx下

# 部署：

