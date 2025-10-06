- ALWAYS use an existing Salesforce DX MCP Server tool before calling the `sf` CLI. THIS IS IMPORTANT. DO NOT FORGET.
- You MUST ALWAYS use the Salesforce DX MCP server's `sf-deploy-metadata` tool, not the Salesforce CLI. 
- NEVER use the Salesforce CLI for deployment UNLESS the Salesforce DX MCP service is unavailable.

# General Requirements
- Do not create UtilityBars for Lightning Apps
- Add all Custom Objects and Flexipage custom tabs to the Custom Application as tabs
- Create unit tests for Apex classes and Lightning Web Components
- Do not create a new README.md file. Append any new text to the end of the file

# Custom Objects
- Always use an Autonumber field for all custom object Name fields
- Do not make any custom fields required
- Always create a custom tab for each custom object
- Create a page layout for each custom object and add all custom fields to the layout

# User Interface
- Create only 1 Lightning Web Components for the application

## Tabs
- Create a custom tab for each Flexipage
- Create a custom tab for each Custom Object

# Permission Set Requirements
- Provide full access to the application, custom objects and all of their custom fields, and any tabs
- Ensure the Permission Set provides access to all tabs
