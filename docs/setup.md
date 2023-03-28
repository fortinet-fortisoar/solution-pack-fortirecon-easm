| [Home](../README.md) |
|----------------------|
# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.   
2. From the list of solution pack that appears, search for and select **FortiRecon EASM**.    
3. Click the **FortiRecon EASM** solution pack card.   
4. Click the **Install** button on the bottom to begin the installation.

## Prerequisites

The **FortiRecon EASM** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| Solution Pack Name | Version          | Purpose                                                  |
|:-------------------|:-----------------|:---------------------------------------------------------|
| SOAR Framework     | v2.0.0 and later | Required for Incident Response modules                   |
| SOC Simulator      | v1.0.1 and later | Required for Scenario Module and SOC Simulator connector |

# Configuration

For optimal performance of the **FortiRecon EASM** solution pack, you must configure:

- Fortinet FortiRecon EASM connectors to get certificate issues
    - To configure and use the Fortinet FortiRecon EASM connector, refer to [Configuring Fortinet FortiRecon EASM](https://docs.fortinet.com/fortisoar/connectors/fortinet-fortirecon-easm)

- ServiceNow connector to log a ticket for fixing certificate issues detected by FortiRecon EASM
    - To configure and use the ServiceNow connector, refer to [Configuring ServiceNow](https://docs.fortinet.com/fortisoar/connectors/servicenow-v2-0-1)
