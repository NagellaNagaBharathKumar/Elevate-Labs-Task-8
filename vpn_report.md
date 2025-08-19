# VPN Usage Report

## Overview
This report documents the use of **ProtonVPN** on Windows to demonstrate how VPNs secure communication by hiding IP addresses and encrypting data.

## Screenshots and Analysis

### 1. Original IP (Before VPN)
- **File:** `vpn_ip_before.png`  
- **Details:**  
  - IPv4: `106.222.234.81`  
  - ISP: Bharti Airtel Ltd.  
  - Location: Hyderabad, India  
- This represents the real ISP-assigned IP address before enabling VPN.

### 2. VPN Connected (ProtonVPN)
- **File:** `vpn_connected.png`  
- **Details:**  
  - VPN Server: Netherlands (NL-FREE#30)  
  - Protocol: WireGuard (UDP)  
  - VPN IP: `185.177.125.90`  
- ProtonVPN successfully established a secure tunnel to a Netherlands server.

### 3. Changed IP (After VPN)
- **File:** `vpn_ip_after.png`  
- **Details:**  
  - IPv4: `185.177.125.90`  
  - ISP: WorldStream B.V. (VPN server provider)  
  - Location: Naaldwijk, Zuid-Holland, Netherlands  
- Confirms that traffic is being routed through ProtonVPN and original IP is hidden.

## Key Benefits of VPN
- Hides real IP and location.  
- Encrypts traffic to prevent interception on public Wi-Fi.  
- Helps bypass geo-restrictions.  
- Adds a layer of anonymity while browsing.  

## Limitations
- Free VPNs may have limited servers and slower speed.  
- VPNs do not protect against phishing or malware.  
- Some websites may block VPN IPs.  

## Conclusion
By connecting through ProtonVPN, the real IP (India) was successfully masked with a VPN-assigned IP (Netherlands).  
This task demonstrated how VPNs enhance privacy and provide secure internet usage.
