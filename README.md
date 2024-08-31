# Monitoring and Securing the DFI Environment

## Project Overview
The "Monitoring and Securing the DFI Environment" project focuses on enhancing the security and monitoring capabilities of the DFI computing environment. This project involves a comprehensive analysis of system configurations, identification of vulnerabilities, and implementation of security measures to protect sensitive data and ensure compliance with industry standards.

## Table of Contents
- [Project Goals](#project-goals)
- [Installation](#installation)
- [Usage](#usage)
- [Findings and Recommendations](#findings-and-recommendations)
- [Automation Opportunities](#automation-opportunities)
- [Contributing](#contributing)

## Project Goals
The primary goals of this project include:
- Assessing the security configuration of Windows and Linux servers.
- Identifying and modifying file permissions to enhance security.
- Recommending unnecessary roles and services to be removed or disabled.
- Implementing encryption methods for data in transit.
- Exploring automation opportunities to improve security management.

## Installation
To set up the project environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/slakshya2/Securing-the-Perimeter.git

2.Navigate to the project directory:
cd Monitoring-and-Securing-the-DFI-Environment

## Usage
This project includes various scripts and documentation to assist in monitoring and securing the DFI environment. Follow the instructions in the respective scripts to perform security assessments, configure firewalls, and analyze system logs.

Key Steps in the Project:
Connecting to the Environment: Establish connections to Windows Workstation via RDP and Linux servers via SSH. Ensure to take screenshots for documentation.
Security Analysis: Conduct a thorough analysis of file permissions, roles, and running services on both Windows and Linux servers.
Encryption Implementation: Choose an appropriate encryption method for securing data in transit and provide justifications for the choice.
Automation Recommendations: Identify areas where automation can be deployed to enhance security management.
Update Management: Provide a table of recommended updates for installation and those that can be skipped, along with justifications.

## Findings and Recommendations
Throughout the project, several key findings were identified, including:

File Permissions: Modifications are necessary for the HR Directory to restrict access.
Unnecessary Roles: Certain roles on the Windows server were found to be redundant and should be removed to minimize attack surfaces.
Service Management: Recommendations were made to disable non-essential services running on both servers to enhance security.
For detailed findings and specific recommendations, please refer to the reports included in the reports/ directory.

## Automation Opportunities
The following areas were identified for potential automation within the DFI environment:

Active Directory: Implement automatic account lockout after multiple failed login attempts from geographically distant IPs.
Log Monitoring: Automate the monitoring of security logs to alert administrators of suspicious activities.
Patch Management: Develop a script to automate the installation of critical and security updates.
## Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, please create an issue or submit a pull request. Ensure that your contributions align with the project's goals and enhance the security measures of the DFI environment.

