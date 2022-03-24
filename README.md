### MakeItGreen

在每日 00:00<sup>UTC</sup> 自动发起一次 commit，可以通过修改 README 等任意更新操作手动触发一次，你也可以修改 `MakeItGreen.yml` 自定义触发时间。由于 GitHub Actions 的机制，它可能并不是那么准时。

### Usage

它通过记录在 secrets 中的邮箱将 commit 信息与账号关联，从而完全避免了在代码中填写明文邮箱造成的邮箱泄露（如果你在意这一点）；其发起的 commit 是完全空白的，他人也无法通过 commit 信息获取邮箱。

使用方法：

- [复制此仓库内容](https://github.com/AstralLing/MakeItGreen/generate)
- 在仓库的 secrets 中添加一条 `EMAIL` 并填入 GitHub 账号使用的邮箱
- Have fun!

只是随手写的一个小玩具，暂时不清楚 fork / generate 之后环境变量能否正常工作……欢迎 issue !
