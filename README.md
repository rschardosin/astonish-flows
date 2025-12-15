# Astonish Alternative Flows Store 🔮

Collection of AI automation flows for [Astonish](https://github.com/schardosin/astonish).

## Available Flows

| Flow | Description |
|------|-------------|
| `simple_web_search_agent` | Simple Agent to Respond to User Questions with Web Search |

## Usage

```bash
# List available flows
astonish flows store list

# Install a flow
astonish flows store install simple_web_search_agent

# Run an installed flow
astonish flows run simple_web_search_agent
```

## Contributing

Want to add a flow to the official store? Submit a PR with:
1. Your flow YAML in `flows/`
2. Update `manifest.yaml` with your flow metadata

## License

MIT
