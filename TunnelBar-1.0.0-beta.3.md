# TunnelBar 1.0.0 beta 3

- Adds v3 endpoint-native tunnel creation for modern ngrok configs.
- Adds Advanced tunnel options for common HTTP, security, metadata, and upstream settings.
- Adds editing for existing configured tunnels, including safe renames for saved groups.
- Validates candidate ngrok config changes before saving, so invalid YAML is rejected without replacing the current config.
- Quotes wildcard domains and other YAML-sensitive values correctly.
