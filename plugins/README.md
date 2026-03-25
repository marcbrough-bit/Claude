# Plugin Marketplace

Manage and install plugins from marketplace sources.

## Structure

- `marketplace.json` - Registered marketplace sources
- `installed.json` - Currently installed plugins
- `<plugin-name>/` - Installed plugin directories

## Installed Plugins

### marketing-skills (v1.0.0)
Source: `coreyhaines31/marketingskills`

Skills included:
- **Content Strategy** - Plan and develop content strategies
- **SEO Optimization** - Optimize content for search engines
- **Email Campaigns** - Design email marketing campaigns
- **Social Media** - Create and manage social media content
- **Analytics & Reporting** - Analyze marketing performance data

## Usage

```
# Add a marketplace source
/plugin marketplace add <owner>/<repo>

# Install a plugin from a marketplace
/plugin install <plugin-name>

# List installed plugins
/plugin list
```
