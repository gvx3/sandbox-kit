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

- Clone this kit somewhere and in the current repository where the agent needs to work on:

```bash
sbx run ./path/to/kit/ --name sandbox-name pi
```
