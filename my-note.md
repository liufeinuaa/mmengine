# 为了自己的项目开发方便，从git上fork下来的官方mmengine

- 创建了自己的开发分支 dev_lf ，主分支保持官方的main不变，方便将官方的更新合并到main中，并于自己的dev分支进行比对
- 设想：以后的开发都基于这个能不断跟进官方更新的工程开发

## dev_lf 分支所做的修改
- 修复 mac m1 上 模型val时候存在的 autocast 的bug
  参考的修复 https://github.com/open-mmlab/mmengine/pull/587/files


