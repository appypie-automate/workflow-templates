# Appy Pie Automate — Workflow Templates

<p align="center">
  <a href="https://appypieautomate.ai"><strong>appypieautomate.ai</strong></a> ·
  <a href="https://helpdesk.appypieautomate.ai/portal/en/kb/automate">Docs</a> ·
  <a href="https://www.appypieautomate.ai/integrate/app-directory">Browse Integrations</a> ·
  <a href="https://accounts.appypie.com/register">Get Started Free</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/templates-100%2B-6c3ae8?style=flat-square" />
  <img src="https://img.shields.io/badge/integrations-1000%2B-3a9bd5?style=flat-square" />
  <img src="https://img.shields.io/badge/no--code-automation-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" />
</p>

A curated collection of ready-to-use workflow automation templates for [Appy Pie Automate](https://appypieautomate.ai). One-click import — no coding required.

## Template Categories

### Email & Communication
| Template | Apps | Description |
|----------|------|-------------|
| Gmail to Slack | Gmail + Slack | Forward important emails to a Slack channel |
| New Email to CRM | Gmail + HubSpot | Create a contact for every new email sender |
| Weekly digest | Gmail + Notion | Summarize emails into a Notion page |

### E-commerce & Sales
| Template | Apps | Description |
|----------|------|-------------|
| New order alert | Shopify + Slack | Notify team on every new Shopify order |
| Order to Sheet | Shopify + Google Sheets | Log orders to a spreadsheet automatically |
| Abandoned cart | Shopify + Mailchimp | Send recovery email for abandoned carts |

### Marketing & Leads
| Template | Apps | Description |
|----------|------|-------------|
| Form to CRM | Typeform + HubSpot | Add form submissions as CRM contacts |
| New lead alert | HubSpot + Slack | Alert sales team on new leads |
| Subscribe to welcome | Mailchimp + Gmail | Send welcome email to new subscribers |

### Project Management
| Template | Apps | Description |
|----------|------|-------------|
| GitHub issue to Jira | GitHub + Jira | Sync GitHub issues to Jira automatically |
| Slack to Trello | Slack + Trello | Create Trello cards from Slack messages |
| New task to Calendar | Asana + Google Calendar | Block time for new Asana tasks |

### Payments & Finance
| Template | Apps | Description |
|----------|------|-------------|
| New payment alert | Stripe + Slack | Notify on successful Stripe charges |
| Invoice to Sheet | Stripe + Google Sheets | Log invoices to spreadsheet |
| Failed payment | Stripe + Gmail | Email customer on failed payment |

## How to Use a Template

1. Browse templates at [appypieautomate.ai](https://appypieautomate.ai)
2. Click the template you want
3. Connect your app accounts (one-time OAuth)
4. Customize field mappings if needed
5. Activate — your automation is live!

## Contributing

Have a useful workflow template? We welcome contributions!

1. Fork this repo
2. Add your template as a `.json` file in the appropriate category folder
3. Include a description in your template's README
4. Open a pull request

### Template Format

```json
{
  "name": "Gmail to Slack",
  "description": "Forward new Gmail emails to a Slack channel",
  "trigger": { "app": "gmail", "event": "new_email" },
  "actions": [
    { "app": "slack", "action": "send_message", "fields": { "channel": "#general" } }
  ],
  "tags": ["email", "communication", "notifications"]
}
```

## Links

- [appypieautomate.ai](https://appypieautomate.ai)
- [Documentation](https://helpdesk.appypieautomate.ai/portal/en/kb/automate)
- [All Integrations](https://www.appypieautomate.ai/integrate/app-directory)

## License

MIT © [Appy Pie LLP](https://appypieautomate.ai)
