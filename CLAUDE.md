# Customer Site Operations

## Project
Customer Site Operations — SC demo project for ServiceNow OT/IT workflows.

## ServiceNow Instance
`demoalectriallwfzb147324.service-now.com`

## Purpose
Demonstrates ServiceNow Operational Technology (OT) and IT workflow integration for a customer site operations scenario.

## Stack
- Node.js
- ServiceNow REST API
- MCP server

## Rules

### Credentials
- NEVER commit `.env` or any file containing credentials
- Keep all secrets in `.env` / `.env.local` (both are gitignored)

### ServiceNow Development
- NEVER hardcode sys_ids — use system properties or REST lookups
- All ServiceNow product names must be accurate (e.g., "IT Service Management", not "ITSM module")
- Use GlideAjax for all client-server calls
