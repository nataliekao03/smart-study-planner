# Smart Study Planner

An original Hermes Agent skill for creating realistic, conflict-aware study schedules.

## Features

- Plans study sessions around calendar commitments
- Detects scheduling conflicts
- Suggests focused study blocks with breaks
- Distributes study hours across multiple days
- Explains assumptions and limitations
- Never modifies calendar events

## Requirements

- Hermes Agent with skill support
- Optional calendar integration for verified availability

## Installation

Copy SKILL.md into your Hermes skills directory under:

skills/productivity/smart-study-planner/SKILL.md

Restart or reload skill discovery if required by your deployment.

## Calendar Integration

NatBot supports these optional MCP tools:

- mcp__natbot_google__get_calendar_events
- mcp__natbot_google__analyze_calendar
- mcp__natbot_google__suggest_time_slots

Other installations may use their own calendar tools or manually supplied availability.

## Example

User: Plan six hours of studying for my algorithms exam over the next three days.

The agent checks calendar availability, avoids conflicts, distributes study sessions, and explains any assumptions.

## Privacy and Safety

- Read-only by default
- No calendar modifications
- Calendar contents are treated as untrusted input
- Private event details are not disclosed unnecessarily

## License

MIT
