# Complete Risk Assessment (Example)

## 1. Asset Overview
Asset: Web Server  
Owner: IT Operations  
Classification: Confidential  

## 2. Threat & Vulnerability
Threat: Man-in-the-Middle attack  
Vulnerability: Weak SSL/TLS configuration  
Description: Outdated TLS versions and weak cipher suites may allow interception of traffic.

## 3. Risk Scoring
Likelihood: 3 (Possible)  
Impact: 4 (Major)  
Risk Score: 12 (High)

## 4. Business Impact
- Exposure of sensitive data
- Loss of customer trust
- Regulatory non-compliance

## 5. Existing Controls
- Firewall in place
- HTTPS enabled
- Monitoring enabled

## 6. Recommended Controls
- Disable TLS 1.0/1.1
- Enforce TLS 1.2/1.3
- Enable HSTS
- Use strong cipher suites
- Regular SSL scans (e.g., Rapid7)

## 7. Risk Treatment
Treatment: Reduce  
Responsible: Security Engineer  
Target Date: 30 days

## 8. Residual Risk
Residual Likelihood: 2  
Residual Impact: 3  
Residual Score: 6 (Medium)

## 9. Approval
Approved by: CISO or TISO 

