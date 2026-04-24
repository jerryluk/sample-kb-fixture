# Integrations

Connect the product to your existing tools and workflows.

## Slack

Install the Slack app and invite the bot to a channel. It responds to `@mention` queries.

## Zapier

Use the Zapier integration to trigger workflows based on events.

## Webhooks

Configure webhooks at **Settings → Webhooks** to receive real-time event notifications.

### Payload format

```json
{
  "event": "article.created",
  "timestamp": "2026-04-24T00:00:00Z",
  "data": { "id": "abc123" }
}
```
