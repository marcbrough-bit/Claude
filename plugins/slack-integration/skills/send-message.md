# Send Message Skill

## Overview
Send messages to Slack channels or users with rich formatting and attachments.

## Commands

### send-text
Send a plain text or markdown-formatted message to a Slack channel or user.

**Parameters:**
- `channel` - Target channel name or ID (e.g., #general, @username)
- `message` - Message content (supports Slack markdown)
- `as_bot` - Whether to send as the bot user (default: true)

### send-block
Send a rich Block Kit message with structured layouts, buttons, and interactive elements.

**Parameters:**
- `channel` - Target channel name or ID
- `blocks` - Block Kit JSON structure defining the message layout
- `fallback_text` - Plain text fallback for notifications

### send-thread-reply
Reply to an existing message thread in a Slack channel.

**Parameters:**
- `channel` - Channel containing the thread
- `thread_ts` - Timestamp of the parent message
- `message` - Reply content
