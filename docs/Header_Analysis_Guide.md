# Header Analysis Guide

This guide helps analysts investigate email headers to identify spoofing, source, and suspicious behavior.

## Key Headers to Analyze

| Header         | Description                                     |
|----------------|-------------------------------------------------|
| `Received:`    | Trace the path the email took through servers   |
| `From:`        | Displayed sender email address                  |
| `Return-Path:` | Bounce-back address (can reveal spoof attempts) |
| `Reply-To:`    | Where replies will be sent                      |
| `SPF/DKIM/DMARC` | Email authentication checks                    |

## Steps
1. Extract full headers from the email client.
2. Paste into a header analysis tool (e.g., Google Admin Toolbox).
3. Look for mismatches in domain names and anomalies.