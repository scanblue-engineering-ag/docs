---
id: integration
title: Scanblue 3D player integration
sidebar_label: Data Protection
---

## Privacy and Data Protection

The Scanblue Player collects usage data. We use the Microsoft Azure Blob Storage to store Microsoft Azure Monitor and Microsoft Application Insights data and we use a dedicated partition for Application Insights data. The article focuses on the Scanblue Player which only collects applicaton data. 

>Note: You can use the following text on your website to inform users that the usage of the Scanblue Player is beeing monitored. 
Find our more about the what data is collected in the this [blogpost]().

## Scanblue Player Usage Data

The Scanblue.Cloud Player includes a telemetry feature that collects usage information. It's important that the Scanblue.Cloud developer team understands how the tools are used so they can be improved.

### Data points

The feature collects the following data:
•	Timestamp of invocation
•	Events invoked
•	Three octet IP address used to determine geographical location
•	Operating system and version
•	Browser Version
•	Hashed MAC address: a cryptographically (SHA256) anonymous and unique ID for a machine.

The feature **doesn't collect personal data, such as usernames or email addresses. It doesn't scan your data or read your cookies and doesn't extract sensitive data, such as name, email** or similar. The data is sent securely to Microsoft servers using the Microsoft Azure Application Insights technology, held under restricted access, and published under strict security controls from secure Azure Storage systems. Find out more about the Legal Service Level Agreements for the Microsoft Products at the [Microsoft Data Protection](https://servicetrust.microsoft.com/ViewPage/GDPRGetStarted) website. The Scanblue Engineering Team stores the collected data points in the geo-regions "Northern Europe" (Dublin, Ireland) and "Western Europe" (Amsterdam, Netherlands).
The Scanblue.Cloud developer team wants to know how the tools are used and if they're working well. If you suspect that the telemetry is collecting sensitive data or that the data is being insecurely or inappropriately handled, file an issue [privacy@scanblue.com](mailto:privacy@scanblue.com).
