# Maya AI MCP

Connect an authorized [Maya AI](https://withmaya.ai/) workspace to compatible AI assistants using the Model Context Protocol. Maya AI is an AI visibility platform for brands and agencies.

This repository contains public integration guidance for Maya's hosted MCP service. Server implementation source code is not included.

## Connect

Use this remote MCP server URL in an MCP-compatible client:

```text
https://withmaya.ai/api/mcp/v1/mcp
```

Authorize through the supported OAuth flow, or use a Maya API bearer token as described in the [developer documentation](https://withmaya.ai/developers). Keep tokens in your client's secure credential settings; never commit them to a repository or paste them into an issue. Available capabilities depend on your workspace and permissions.

## Example questions

- What changed in our AI visibility this week?
- Which competitors appear alongside our brand?
- Which sources are cited in answers about our category?
- What action items should our team prioritize?

## Public resources

- [Maya AI website](https://withmaya.ai/)
- [Developer resources and authentication](https://withmaya.ai/developers)
- [OpenAPI specification](https://withmaya.ai/openapi.json)
- [REST API discovery](https://withmaya.ai/api/v1)
- [Integration documentation](https://withmaya.ai/docs)

## Troubleshooting

If authorization fails, check the selected workspace, permissions, and token validity. Confirm that your client supports remote MCP connections and the selected authentication method. Do not include credentials or private workspace data in public support requests.

Connection and authentication details above are based on Maya's official developer resources. Refer to those resources for current endpoint and client support details.
