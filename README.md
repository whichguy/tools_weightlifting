# Weightlifting Tools

Dynamic tools for querying USAW (USA Weightlifting) and IWF (International Weightlifting Federation) data.

## Usage

Add the raw GitHub URL to your `_ToolSources` sheet to enable auto-sync:

```
https://raw.githubusercontent.com/jameswiese/tools_weightlifting/main/tools.json
```

## Tools (14)

### USAW Rankings & Athletes
| Tool | Description |
|------|-------------|
| `usaw_rankings` | Get rankings by weight class and date range |
| `usaw_weight_classes` | Get weight class IDs and labels |
| `usaw_lifter_history` | Get competition history for one athlete |
| `usaw_bulk_lifter_history` | Get competition history for multiple athletes |
| `usaw_search_athlete` | Search for athlete by name across weight classes |
| `usaw_wso_records` | Get WSO all-time best lifts per weight class |
| `usaw_filter_options` | Get available filter options for USAW tools |

### USAW Events
| Tool | Description |
|------|-------------|
| `usaw_events` | List events/competitions by date range |
| `usaw_event_results` | Get results from USAW events |
| `usaw_event_entries` | Get registered lifters for upcoming events |
| `usaw_upcoming_events` | List upcoming events with registration info |

### IWF (International)
| Tool | Description |
|------|-------------|
| `iwf_world_records` | Get IWF World Records by gender/age group |
| `iwf_events` | List IWF events by year |
| `iwf_event_results` | Get results from an IWF event |

## Data Sources

- **USAW**: USA Weightlifting Rankings API (admin-usaw-rankings.sport80.com)
- **IWF**: International Weightlifting Federation (iwf.sport)

## License

MIT
