# Notifications Skill

## Overview
Configure automated notifications for build status, deployments, and workflow events.

## Commands

### setup-webhook
Configure an incoming webhook URL for a Slack channel to receive automated messages.

**Parameters:**
- `channel` - Target channel for the webhook
- `webhook_url` - Slack incoming webhook URL
- `label` - Friendly name for this webhook configuration

### configure-alerts
Set up automated alerts that trigger on specific events like CI failures or deployments.

**Parameters:**
- `event_type` - Event to monitor (ci-failure, ci-success, deploy, pr-merged, pr-review-requested)
- `channel` - Channel to send alerts to
- `severity` - Alert severity filter (all, warning, error, critical)
- `mention` - Users or groups to mention (@here, @channel, or specific users)

### schedule-digest
Schedule a recurring digest message summarizing activity over a time period.

**Parameters:**
- `channel` - Channel to post the digest in
- `frequency` - How often to post (daily, weekly, biweekly)
- `time` - Time to post (HH:MM in UTC)
- `include` - Topics to include (commits, prs, issues, deployments, metrics)
