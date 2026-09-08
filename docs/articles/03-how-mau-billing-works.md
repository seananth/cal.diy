# How monthly active users are counted

Sunboard plans are priced by **monthly active users (MAU)**: the number of distinct users your apps identify to Sunboard in a billing month.

## What counts as active

A user counts once per billing month, the first time any of your projects identifies them in that month. It doesn't matter how many sessions they have, how many projects they appear in, or whether they interact with a checklist or tour: one identified user is one MAU. Users who never get identified in a month don't count for that month.

Sandbox traffic follows the same rule but is far smaller in practice, since it's your team testing rather than real users.

## How this relates to your plan

Each plan includes an MAU allowance for the workspace as a whole, across all its projects. The Billing tab in Settings shows where you are in the current month.

Two things to know about approaching the limit:

- **Nothing turns off.** Going over your allowance never disables experiences or drops users mid-onboarding. Your onboarding keeps working.
- **You'll hear from us instead.** Workspace owners and admins get an email when usage passes roughly 80% of the allowance, and the dashboard shows a notice if you go over, with a prompt to move up a plan.

## Why MAU and not something else

MAU tracks the value Sunboard provides: users actually going through your onboarding. Seats would penalize adding teammates (we'd rather your whole team is in here), and per-experience pricing would penalize experimenting, which is the opposite of what good onboarding needs.

## Common questions

**A user visited in January and again in March. Two MAU?** They count once in January's month and once in March's. February, when they never appeared, costs nothing.

**Do team members count?** If your app identifies them to Sunboard like any other user, yes, they're indistinguishable from real users. Most teams exclude internal accounts in their own identify call.

**What happens on downgrade?** Your allowance changes at the next billing cycle; the same notification rules apply against the new number.
