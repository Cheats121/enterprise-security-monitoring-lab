# Wazuh Configuration

This directory contains sanitized configuration snippets used in the
Enterprise Security Monitoring Lab.

## Files

### `virustotal-integration.xml`
Integrates Wazuh File Integrity Monitoring events with VirusTotal for
file-hash reputation checks.

### `windows-fim-config.xml`
Enables real-time monitoring of Desktop and Downloads directories for
Windows users.

### `windows-defender-events.xml`
Collects Microsoft Defender operational events so malware detections
can be forwarded to Wazuh.

> Sensitive values such as API keys and internal addresses have been
> removed or replaced with placeholders.
