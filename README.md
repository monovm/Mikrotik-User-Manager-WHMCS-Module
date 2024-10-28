# MikroTik User Manager WHMCS Module #
The MikroTik User Manager WHMCS Module integrates MikroTik's User Manager with WHMCS, providing a comprehensive solution for automated user management, billing, and network control. This module enables resellers and network administrators to streamline service provisioning, billing, and access control directly within the WHMCS platform.

## Features ##
Automated User Management: Automatically create, suspend, and terminate users in MikroTik User Manager based on WHMCS billing and provisioning.
Prepaid and Postpaid Billing: Flexible billing options allow for both prepaid and postpaid billing models.
Data and Time Limit Management: Configure data and time limits for user access according to service plans.
User Authentication: Integrate user authentication with MikroTik’s User Manager directly from WHMCS.
Service Control: Manage internet speed limits, session time, and bandwidth allocation through WHMCS.
## Requirements ##
WHMCS Version: Compatible with WHMCS 8.0 and above.
MikroTik RouterOS: Requires MikroTik router with RouterOS supporting User Manager.
API Access: Ensure MikroTik API access is enabled.
PHP Version: Requires PHP 7.4 or above.
## Installation ##
### 1. Download the Module ###
Download the latest release from the GitHub repository.

### 2. Upload to WHMCS ###
Unzip the downloaded file.
Upload the module files to the /modules/servers/mikrotik_user_manager/ directory in your WHMCS installation.
### 3. Activate the Module ###
Log in to your WHMCS Admin Panel.
Go to Setup > Products/Services > Servers.
Click Add New Server and configure the MikroTik server with your API credentials.
### 4. Configure Product ###
Go to Setup > Products/Services > Products/Services.
Click Create a New Product and select MikroTik User Manager as the module.
Customize the product settings as needed to match your network service plans.
## Configuration ##
### API Settings ###
Navigate to Setup > Products/Services > Servers in WHMCS.
Select the MikroTik User Manager server.
Enter your MikroTik API host, username, password, and other required credentials.
Test the connection to ensure successful integration.
### Product Options ###
Customize the following options according to your network setup:

Bandwidth and Speed Limits: Set bandwidth and speed limits per plan.
Session and Data Limits: Define data usage and session time limits.
Billing Cycles: Select from prepaid or postpaid billing options.
## Usage ##
Once installed and configured, customers can manage their MikroTik User Manager access directly from the WHMCS client area. The module handles provisioning, suspension, and termination based on WHMCS billing cycles and usage limits.

## Support ##
For issues or support, contact MonoVM Support or use the GitHub Issues page for community assistance.

## License ##
This module is licensed under the MIT License.

## Contribution ##
We welcome contributions! Fork the repository, submit pull requests, or open issues for any improvements or bug fixes.
