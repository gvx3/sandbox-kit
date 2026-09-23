# sandbox-kit

Docker sandbox kit for spinning up an isolated environment for Pi agent with Deepseek API.

- Create secret for storing API key:

```bash
sbx secret set-custom \
    --host api.deepseek.com \
    --env DEEPSEEK_API_KEY \
    --value "VALUE"
```

> [!WARNING]
> Delete the history of shell's command since the API key value is there
