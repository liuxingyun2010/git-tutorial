### git 技巧练习

- 回到远程仓库的状态
  如果在暂存区或者本地仓库，更新的文件会被还原掉；工作区中的不会

  ```bash
    git fetch --all && git reset --hard origin/master
  ```

- 将暂存区的所有改动重新放回到工作区，并且清空所有 commit(慎用)

  ```bash
    git update-ref -d HEAD
  ```
