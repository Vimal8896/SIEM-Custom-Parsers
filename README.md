# SIEM Custom Parsers

A collection of custom parsers developed for Security Information and Event Management (SIEM) platforms to normalize, enrich, and structure security logs from various sources. These parsers are designed to improve log visibility, threat detection, and security monitoring across different environments.

## Overview

This repository contains custom-built parsers used for transforming raw log data into structured events that can be efficiently queried, analyzed, and correlated within SIEM platforms.

The parsers are developed to support:

* Microsoft Sentinel
* Google SecOps (Chronicle)
* Common Event Format (CEF)
* JSON-based log sources
* Syslog integrations
* Custom application logs
* Cloud and security product integrations

## Features

* Log normalization and field extraction
* Parsing support for JSON, Syslog, and CEF formats
* Security-focused field mapping
* Timestamp normalization
* Vendor-specific log transformation
* Easy customization and extension
* Production-tested parser logic

## Repository Structure

```text
SIEM-Custom-Parsers/
│
├── Microsoft-Sentinel/
│   ├── Parser-1
│   ├── Parser-2
│   └── ...
│
├── Google-SecOps/
│   ├── Parser-1
│   ├── Parser-2
│   └── ...
│
├── CEF-Parsers/
│   ├── Parser-1
│   ├── Parser-2
│   └── ...
│
└── Documentation/
```

## Supported Log Sources

The repository may include parsers for:

* Firewall Logs
* Endpoint Security Logs
* Cloud Audit Logs
* SaaS Application Logs
* Identity and Access Logs
* Network Security Logs
* Custom Application Logs
* Threat Intelligence Feeds

## Use Cases

### Log Normalization

Convert vendor-specific log formats into a standardized schema.

### Security Monitoring

Enable efficient threat hunting and security investigations.

### Detection Engineering

Support analytics rules, detections, and alerting workflows.

### Compliance Reporting

Improve visibility for audit and compliance requirements.

## Prerequisites

Before using these parsers, ensure:

* Access to the target SIEM platform
* Required permissions to create or modify parsers
* Sample log data for testing
* Understanding of the source log format

## Deployment

1. Download the required parser.
2. Import or configure it in your SIEM platform.
3. Validate parsing against sample logs.
4. Verify field mappings and normalization.
5. Deploy to production.

## Testing

Recommended validation steps:

* Verify timestamp extraction
* Confirm field mappings
* Validate event categorization
* Test against multiple log samples
* Check parsing performance and accuracy

## Contributing

Contributions are welcome.

If you would like to improve existing parsers or add support for new log sources:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a Pull Request

## Disclaimer

These parsers are provided as-is without warranty. Thoroughly test all parser logic in a non-production environment before deployment.

## Author

**A. R. Vimal Kumar**

SIEM Engineer | Microsoft Sentinel | Google SecOps | Security Monitoring | Log Ingestion | Detection Engineering

## License

This project is licensed under the MIT License.

