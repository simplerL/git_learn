HEAD 指向的版本就是当前版本，因此，Git允许我们在版本历史之间穿梭，使用命令 `git reset --hard commit_id`;
穿梭前，可以使用 `git log` 查看提交的历史记录，以便确定要回退的版本;
要重返未来，用`git reflog`查看命令历史，以便自己确定要回到未来的那个版本;