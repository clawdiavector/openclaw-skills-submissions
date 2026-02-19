name: weather-pollen
description: Weather and pollen reports for any location using free APIs. Get current conditions, forecasts, and pollen data.
metadata: {"clawdbot":{"emoji":"🌤️","requires":{"bins":["curl"]}}}

# Weather and Pollen Skill

Get weather and pollen reports for any location using free APIs.

## Usage

When asked about weather or pollen in Anna, TX (or configured location), use the `weather_report` tool from this skill.

## Tools

### weather_report
Get weather and pollen data for a specified location.

**Args:**

**Example:**
```json
{"includePollen": true, "location": "Anna, TX"}
```

## Configuration

Set location via environment variables (defaults for Anna, TX):

## APIs Used
