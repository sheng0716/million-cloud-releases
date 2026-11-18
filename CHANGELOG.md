# Release notes

Every Million Cloud test build, newest first. The latest APK is on the
[Releases page](https://github.com/sheng0716/million-cloud-releases/releases/latest).

## v1.1.0 (2026-11-18)

Installs over v1.0.0, so you don't need to uninstall first.

### New
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

### Fixed
- Receivable aging bars now draw at their real height.
- A company that refused a report can be tried again without restarting the app.
- Failed requests are no longer retried in the background.

## v1.0.0 (2026-09-21)

The first test build. This version can no longer be downloaded; install v1.1.0 instead.

- Sign in with your Million Cloud account, choose a company, and switch between companies without signing in
  again.
- Six reports: Profit & Loss, Balance Sheet, Trial Balance, Cash Flow, Customer Aging and Supplier Aging. You
  only see the reports your role can open, and you can share any of them as a PDF.
- Dashboard tab with Cash & Bank, overdue payments, and income vs expenses.
- Pull down on any report to refresh it.
