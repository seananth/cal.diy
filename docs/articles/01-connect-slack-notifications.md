# Get Sunboard insights in Slack

Sunboard can post each project's insights digest straight to a Slack channel, so your team sees onboarding problems without opening the dashboard.

Connecting takes two steps: install the Slack app once for your workspace, then pick a channel for each project you want digests from.

## Step 1: Connect your Slack workspace

1. Open **Settings** from the sidebar.
2. Go to the **Workspace** tab and find the **Slack** card.
3. Click **Connect**. A Slack window opens asking you to authorize Sunboard.

![Screenshot: the Slack card in workspace settings](images/slack-card.png)

4. Pick the Slack workspace you want and click **Allow**.

When the window closes you should see the card showing **Connected** with your Slack workspace name.

> Note: connecting Slack is workspace-wide in Sunboard, you only do this once. If the card shows **Error**, an admin may have removed the app on the Slack side; reconnecting fixes it.

## Step 2: Choose a channel for your project

Digests are configured per project, so different projects can post to different channels.

1. Open the project you want digests for.
2. Go to the project's **Settings** tab.
3. In the Slack section, choose the channel to post to.

![Screenshot: choosing a channel in project settings](images/slack-channel.png)

That's it. The next insights digest for this project will be posted to the channel you picked, alongside the email digest.

## Turning it off

Clear the channel selection on the project to stop digests for that project, or disconnect the workspace from the Slack card in Settings to stop everything at once.
