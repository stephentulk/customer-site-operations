# Customer Site Operations

SC demo project for ServiceNow OT/IT workflow integration.

## Purpose

Demonstrates how ServiceNow can orchestrate Operational Technology (OT) and IT workflows for customer site operations — covering incident detection, asset management, and cross-domain automation.

## ServiceNow Instance

```
https://demoalectriallwfzb147324.service-now.com
```

## Setup

1. **Clone the repo**
   ```bash
   git clone <repo-url>
   cd customer-site-operations
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment**

   Copy the example env file and fill in your credentials:
   ```bash
   cp .env.example .env
   ```

   Required variables:
   ```
   SN_INSTANCE=demoalectriallwfzb147324.service-now.com
   SN_USERNAME=admin
   SN_PASSWORD=<your-password>
   ```

   > **.env is gitignored — never commit credentials.**

4. **Run**
   ```bash
   npm start
   ```

## Project Guidelines

See [CLAUDE.md](./CLAUDE.md) for development rules, including ServiceNow conventions and credential handling policies.
