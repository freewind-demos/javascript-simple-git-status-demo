JavaScript "simple-git" "git status" Demo
=========================================

使用"simple-git"将指定的git仓库clone到本地，然后查看status

```
npm install
node run demo
```

在`local-repo`目录下看到新clone下来的`demo-project`，并且会显示它的status:

```
cloned to: local-repo/demo-project
StatusSummary {
  not_added: [],
  conflicted: [],
  created: [],
  deleted: [],
  modified: [],
  renamed: [],
  files: [],
  staged: [],
  ahead: 0,
  behind: 0,
  current: 'master',
  tracking: 'origin/master' }
```
