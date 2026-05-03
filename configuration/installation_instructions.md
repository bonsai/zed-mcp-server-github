# GitHub MCP Server Authentication

This extension supports two authentication methods:

## OAuth (Recommended)

No configuration required. When you first use the extension without a personal access token, GitHub MCP Server will guide you through the OAuth authentication flow in your browser.

## Personal Access Token

If you prefer to use a personal access token:

1. Go to your account's [Developer Settings](https://github.com/settings/tokens/new?description=zed-mcp-server-github&scopes=repo)
2. Create a Personal Access Token with `repo` scope
3. Add it to your extension settings:

```json
{
  "github_personal_access_token": "your_token_here"
}
```
