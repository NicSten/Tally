# Tally

Budget planner in one offline app: portion out your paychecks, plan bills, see debt payoff dates, and project savings and auto-transfers. Everything is stored on the device.

Live at **https://nicsten.github.io/Tally/**

## Install
1. Open `https://nicsten.github.io/Tally/` on your phone.
2. Android (Chrome): ⋮ → **Install app** (or Add to Home screen). iPhone (Safari): Share → **Add to Home Screen**.

Long-press the home-screen icon (Android) for **Plan**, **Debt** and **Savings** shortcuts.

## Tabs
- **Month**: what's left each month after bills, debt payments and auto-transfers, your debt-free date, net worth, the next 14 days of paydays/bills/transfers, and bills by category.
- **Plan**: paychecks, bills and expenses, and portions (fun money, cushion, …) that split up what's left by percent, per month and per paycheck.
- **Debt**: highest-interest-first or smallest-balance-first payoff, an extra monthly amount, payoff month for each debt, interest saved, and a balance chart against minimums only. Paid-off payments roll into the next debt.
- **Savings**: savings, retirement and investment accounts with their auto-transfers, and 1/5/10-year projections at your own growth estimates.

It opens with example numbers. Tap **Start blank** to clear them, or **Edit these** to change them in place. Tap any row to edit or delete it.

## Moving your data over
Data doesn't follow between the Claude artifact version and this installed version.
In the artifact: ⋯ → Export backup. In the installed app: ⋯ → Import backup and pick that file.

## Tips
- Frequencies: every week, every 2 weeks, twice a month, monthly, every 3 months, yearly. Everything is converted to a monthly average for the plan.
- Set a bill's **Next due** date and Tally works out every date after it.
- `?tab=plan`, `?tab=debt` or `?tab=save` opens straight to that tab.
- Export a backup now and then. iPhone can clear website storage for apps that aren't added to the home screen.

## Updating
After changing any file, bump `CACHE` in `sw.js` (`tally-v2`, …) so the phone picks up the new version. It may take one app restart.
