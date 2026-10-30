# Tally

Budget planner in one offline app: portion out your paychecks, log spending, plan bills, see debt payoff dates, and project savings goals and auto-transfers. Everything is stored on the device.

Live at **https://nicsten.github.io/Tally/**

## Install
1. Open `https://nicsten.github.io/Tally/` on your phone.
2. Android (Chrome): ⋮ → **Install app** (or Add to Home screen). iPhone (Safari): Share → **Add to Home Screen**.

On Android, long-press the home-screen icon for **Log spending**, **Plan**, **Debt** and **Savings** shortcuts.

## Tabs
- **Month**: what's left each month after bills, debt payments and auto-transfers. Also shows how much is left in your portions this month, your debt-free date, net worth, and the next 14 days of paydays, bills and transfers. Tick the circle to mark a bill paid. Bills by category, plus a net worth chart that builds up month by month.
- **Spend**: log what you spend against a portion (fun money, cushion, …) or a category. You see what's left in each portion, a daily amount for the rest of the month, and past months.
- **Plan**: paychecks, bills and expenses, and portions that split up what's left by percent, per month and per paycheck.
- **Debt**: pay off the highest interest or the smallest balance first, add an extra monthly amount, and see a payoff month for each debt, interest saved, and a balance chart against minimums only. When a debt is paid off, its payment rolls into the next one.
- **Savings**: savings, retirement and investment accounts with their auto-transfers, and 1/5/10-year projections at your own growth estimates. Give an account a goal and an optional date to see when you'll reach it, or how much a month it needs.

It opens with example numbers. Tap **Start blank** to clear them, or **Edit these** to change them in place. Tap any row to edit or delete it. Deleting shows an **Undo** button for a few seconds.

## Keeping your data safe
- Export a backup from ⋯ now and then. Tally reminds you on the Month tab after two weeks without one. On iPhone, the export opens the share sheet: choose **Save to Files**.
- Importing a backup, erasing, or loading the examples keeps a copy of what was there before. ⋯ → **Switch to previous budget** brings it back.
- Backups are checked as they're imported, so a damaged or edited file can't break the app.
- With Tally open in two tabs, each picks up the other's changes.

## Moving your data over
Data doesn't move on its own between the Claude artifact version and this installed version.
In the artifact: ⋯ → Export backup. In the installed app: ⋯ → Import backup and pick that file.

## Tips
- Frequencies: every week, every 2 weeks, twice a month, monthly, every 3 months, yearly. Everything is converted to a monthly average for the plan.
- Set a bill's **Next due** date and Tally works out every date after it. Debts due on the 29th–31st land on the last day of shorter months.
- `?tab=spend`, `?tab=plan`, `?tab=debt` or `?tab=save` opens straight to that tab. `?tab=spend&add=1` opens the log-spending sheet.

## Updating
After changing any file, bump `CACHE` in `sw.js` (`tally-v3`, …). The page itself loads from the network first, so phones get updates on the next launch when online.
