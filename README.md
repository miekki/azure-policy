# Azure Policy Repository

Welcome to the Azure Policy repository, where you can efficiently manage Azure Policies through code. This repository is organized into two key folders:

## Initiatives

Navigate to the 'initiatives' folder to find custom initiative definitions. Each subfolder represents an individual initiative, and the 'policy.json' file contains the initiative definition. Additionally, you'll find a 'policyset.json' file that includes the initiative assignment definition.

## Policies

Explore the 'policies' folder to discover custom policy definitions. Each subfolder represents a distinct custom policy, with the 'policy.json' file containing the policy definition.

The policy can be exempt in special circumstances by providing a tag "policy\*exemption" and value should contain the reason for the examptions. Please see the policy definition for the exact tag name. The format should be "policy_exemption_group_policy" eg. "policy_exemption_app_service_require_outbound_VNET"

Feel free to explore, contribute, and collaborate on enhancing Azure Policy management in a code-driven manner!

To help with developing or ammending the policies please install Visual Code extention ["Azure Policy"](https://learn.microsoft.com/en-us/azure/governance/policy/how-to/extension-for-vscode#search-for-and-view-resources)
