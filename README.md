# Mercury Receipts

Automated workflow that finds Mercury transactions missing receipts, searches for matching emails in Gmail, and forwards them to Mercury.

## How it works

1. Queries Mercury for transactions without attached receipts
2. Searches Gmail for receipt emails matching each transaction's merchant and date
3. Forwards matching receipts to receipts@mercury.com
4. Notifies the team on Slack for any transactions where no receipt was found

## Schedule

Runs daily at 9:00 AM GMT+8 via GitHub Actions.

---

Powered by [vm0.ai](https://vm0.ai)
