# Microsoft Sentinel Home SOC Lab

## Overview

This repository documents my hands-on experience building a Home Security Operations Center (SOC) using Microsoft Sentinel and Azure Log Analytics.

The objective of this project was to gain practical experience with cloud-native security monitoring, log collection, and investigation using Microsoft's security ecosystem.

## Technologies Used

- Microsoft Sentinel
- Azure Log Analytics
- Azure Monitor Agent
- Windows Event Logs
- Kusto Query Language (KQL)

## Architecture

Windows Endpoint → Azure Monitor Agent → Log Analytics Workspace → Microsoft Sentinel

## Key Learning Outcomes

- Creating and configuring a Log Analytics Workspace
- Deploying Microsoft Sentinel
- Onboarding Windows endpoints
- Validating log ingestion
- Investigating deployment issues
- Working with Azure Resource Providers

## Challenges Encountered

During deployment, I encountered an issue where Microsoft.OperationalInsights was not registered within the Azure subscription.

After identifying and registering the required Azure Resource Provider, the deployment completed successfully.

This experience reinforced the importance of understanding subscription-level dependencies within Azure.

## Medium Article

Read the full article here:

https://medium.com/@tegaaruvwe/building-my-first-home-soc-with-microsoft-sentinel-and-azure-log-analytics-19e51ac264f3

## Future Improvements

- Add additional data sources
- Create custom analytics rules
- Explore automated incident response
- Build additional cloud security labs

## Author

Tega Avwaghwaruvwe

Cloud Engineer | Microsoft Entra ID | Azure Security | IAM | Cloud Security