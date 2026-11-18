# Release notes · 版本说明

Every Million Cloud test build, newest first. The latest APK is on the
[Releases page](https://github.com/sheng0716/million-cloud-releases/releases/latest).

Million Cloud 每个测试版本的更新内容，最新的在最上面。最新的 APK 在
[Releases 页面](https://github.com/sheng0716/million-cloud-releases/releases/latest)下载。

## v1.1.0 (2026-11-18)

### English

Installs over v1.0.0, so you don't need to uninstall first.

**New**
- **Sales tab**: net sales compared with last year, a monthly chart, a daily calendar, and top customers and top
  products, each with its change on last year. It only appears if your role can see sales reports.
- **Dashboard**:
  - A new layout that starts with your net position, and says what it's made of.
  - Receivable and payable, split into overdue and not yet due.
  - Receivable aging.
  - What falls due in the next 30 days.
- **Stay signed in**: you stay signed in until you sign out or change your password. In v1.0.0 you were signed
  out every 24 hours.
- **Expired subscriptions**: a company whose subscription has ended shows as expired in the company list. If it
  ends while you're using it, the app tells you and goes back to the list.
- A "Forgot password" link on the login screen, and a link to the privacy policy.

**Fixed**
- Receivable aging bars now draw at their real height.
- A company that refused a report can be tried again without restarting the app.
- Failed requests are no longer retried in the background.

### 中文

可以直接覆盖安装在 v1.0.0 上，不用先卸载。

**新功能**
- **Sales tab**：净销售额与去年对比、每月图表、每日日历，以及销售额最高的客户和产品，每一项都显示与去年相比的变化。
  只有你的角色有销售报表权限时才会出现。
- **Dashboard**：
  - 新的布局，最上面是净头寸（Net Position），并说明它由哪些部分组成。
  - 应收和应付，分成已逾期和未到期。
  - 应收账龄。
  - 未来 30 天内到期的款项。
- **保持登录**：除非你自己登出或修改密码，否则会一直保持登录。v1.0.0 每 24 小时就会被登出一次。
- **订阅到期**：订阅已到期的公司会在公司列表中显示为已到期。如果正在使用时订阅到期，app 会提示你并回到公司列表。
- 登录页面新增「Forgot password」（忘记密码）链接和隐私政策链接。

**修复**
- 应收账龄的柱状图现在会按实际高度显示。
- 某个公司的报表被拒绝后，可以直接重试，不用重启 app。
- 请求失败后不会再在后台自动重试。

## v1.0.0 (2026-09-21)

### English

The first test build. This version can no longer be downloaded; install v1.1.0 instead.

- Sign in with your Million Cloud account, choose a company, and switch between companies without signing in
  again.
- Six reports: Profit & Loss, Balance Sheet, Trial Balance, Cash Flow, Customer Aging and Supplier Aging. You
  only see the reports your role can open, and you can share any of them as a PDF.
- Dashboard tab with Cash & Bank, overdue payments, and income vs expenses.
- Pull down on any report to refresh it.

### 中文

第一个测试版本。这个版本已经不能下载了，请安装 v1.1.0。

- 用 Million Cloud 账号登录，选择公司，切换公司时不用重新登录。
- 六个报表：损益表（Profit & Loss）、资产负债表（Balance Sheet）、试算表（Trial Balance）、现金流量表（Cash Flow）、
  客户账龄（Customer Aging）和供应商账龄（Supplier Aging）。只会显示你的角色有权限查看的报表，每个报表都可以导出成
  PDF 分享。
- Dashboard tab：现金与银行（Cash & Bank）、逾期款项、收入与支出。
- 在任何报表上往下拉就可以刷新。
