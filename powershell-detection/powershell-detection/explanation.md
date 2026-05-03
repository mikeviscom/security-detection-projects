## Detection Logic

This detection identifies PowerShell commands executed with encoded parameters, which are commonly used to obfuscate malicious activity.

## Tuning Considerations

- Exclude known administrative scripts
- Filter based on user roles
- Monitor frequency of execution

## Data Sources

- Windows Security Logs (Event ID 4688)
