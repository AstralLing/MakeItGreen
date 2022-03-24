### MakeItGreen

在每日零点自动发起一次 commit，可以通过修改 README 等任意更新操作手动触发一次。

### Usage

它通过记录在 secrets 中的邮箱将 commit 信息与账号关联，从而完全避免了在代码中填写明文邮箱造成的邮箱泄露（如果你在意这一点）。

使用方法：
- Fork 此仓库
- 在仓库的 secrets 中添加一条 `EMAIL` 并填入 GitHub 账号使用的邮箱
  - 如果你开启了隐私保护，填写真实邮箱或是 GitHub 的 `noreply` 邮箱，最终都会呈现为 `noreply` 邮箱。

只是随手写的一个小玩具，暂时不清楚 fork 之后环境变量能否正常工作……欢迎 issue !
