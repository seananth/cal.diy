# Getting started with your Sunboard project

Once you've created a project, three things get you to a working setup: a segment that decides who sees your onboarding, a look at how it's performing, and notifications so you hear about problems without checking the dashboard. This guide walks through all three.

## 1. Create your first segment

Segments route your users to the right experience. A user who matches a segment's rules gets the experience attached to it.

1. Open your project from the sidebar. You'll land on the **Overview** tab.
2. Scroll to the segments area and click **Add segment**.
3. In the **New segment** dialog, give the segment a name your team will recognize (for example "Trial admins").

![Screenshot: the new segment dialog](images/new-segment.png)

4. Add one or more rules. Rules match on user attributes, for example plan equals trial.
5. Click **Create segment**.

Your segment now appears on the Overview tab. Users matching its rules are routed to whatever experience you attach to it. If a user matches several segments, the more specific one wins.

## 2. Check how your onboarding is doing

The **Overview** tab is also where your project's numbers live: how many users started onboarding, step completion, and where people drop off. Early on the numbers will be small; the thing to build a habit around is checking the drop-off pattern after each change you ship.

## 3. Get insights in Slack

Sunboard watches your onboarding analytics and raises insights when something looks wrong, for example a step that suddenly loses more users than usual. You can get these as a digest in Slack:

1. Open **Settings** from the sidebar and connect Slack from the **Workspace** tab (one-time, workspace-wide).
2. Back in your project's **Settings** tab, pick the channel digests should post to.

See "Get Sunboard insights in Slack" for the full walkthrough.

## What's next

Attach an experience to your segment and deploy it to the sandbox environment to see the whole loop working before anything reaches production users.
