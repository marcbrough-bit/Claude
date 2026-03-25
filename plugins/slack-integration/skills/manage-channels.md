# Manage Channels Skill

## Overview
Create, archive, and configure Slack channels for team workflows.

## Commands

### create-channel
Create a new Slack channel with a name, purpose, and initial members.

**Parameters:**
- `name` - Channel name (lowercase, no spaces, max 80 chars)
- `purpose` - Channel purpose description
- `is_private` - Whether the channel is private (default: false)
- `members` - List of user IDs to invite on creation

### set-topic
Set or update the topic and purpose of an existing Slack channel.

**Parameters:**
- `channel` - Channel name or ID
- `topic` - New channel topic
- `purpose` - New channel purpose (optional)

### invite-members
Invite one or more users to a Slack channel.

**Parameters:**
- `channel` - Channel name or ID
- `members` - List of user IDs or email addresses to invite
