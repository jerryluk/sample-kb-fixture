# Authentication

All API requests require authentication via an API key.

## Generating an API Key

1. Log in to the admin dashboard
2. Navigate to **Settings → API Keys**
3. Click **Generate New Key**

## Using Your Key

Pass the key in the `Authorization` header:

```http
Authorization: Bearer YOUR_API_KEY
```

## Token Expiry

Keys do not expire by default. Rotate them periodically for security.

## Scopes

| Scope | Description |
|---|---|
| `read` | Read-only access to all resources |
| `write` | Create and update resources |
| `admin` | Full access including deletion |
