# Commands and permissions

## Commands

| Command | Description | Permission | Usage |
|---------|-------------|------------|-------|
| `/rootrestart` | Graceful server restart with countdown | `` | `/rootrestart [cancel]` |
| `/rootstop` | Graceful stop for update with countdown | `` | `/rootstop [cancel]` |

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `rootrestart.admin` | Start a manual restart or stop-for-update countdown | `op` |
| `rootrestart.cancel` | Cancel a pending restart or stop countdown | `op` |

