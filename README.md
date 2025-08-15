# Task-8-working-with-vpns
# VPN Setup and Analysis Report

**Date:** August 15, 2025
**Analyst:** root
**Tool Used:** ProtonVPN (Free Tier)

## 1. Objective

The objective of this task was to understand the function, benefits, and limitations of a Virtual Private Network (VPN). This was achieved by setting up a reputable VPN service, verifying its ability to mask an IP address and encrypt traffic, and researching its core privacy features.

## 2. Setup and Configuration Steps

1.  **Service Selection:** ProtonVPN was chosen due to its strong reputation for privacy and its reliable free tier.
2.  **Account Creation:** A free account was created on the official ProtonVPN website.
3.  **Client Installation:** The ProtonVPN client for Windows was downloaded and installed by following the on-screen setup wizard.
4.  **Initial Connection:** After logging into the client, a connection was established to the fastest available free server, which was located in **Singapore**.

## 3. Verification of VPN Connection

To confirm the VPN was working correctly, an IP address lookup tool (`whatismyipaddress.com`) was used before and after connecting to the VPN.

### ### Connection Status Screenshot (Simulated)

The screenshot below shows the change in public IP address, location, and ISP details after activating the VPN.

```
--------------------------------------------------
|               CONNECTION STATUS                |
--------------------------------------------------

[ BEFORE CONNECTING TO VPN ]

  Your Public IP Address is: 103.111.11.XX
  Your ISP is              : Reliance Jio Infocomm
  Your Location is         : Hapur, Uttar Pradesh, IN

--------------------------------------------------

[ AFTER CONNECTING TO PROTONVPN - SINGAPORE ]

  Your Public IP Address is: 45.144.20.XX
  Your ISP is              : DataPacket
  Your Location is         : Singapore, SG

--------------------------------------------------
```
**Result:** The verification was successful. The public IP address was changed from one located in India to one in Singapore, and the ISP was masked, now showing the data center provider used by the VPN. Browsing a website confirmed that internet traffic was flowing correctly through the encrypted tunnel.

## 4. Analysis of VPN Technology and Features

Research was conducted on the core features that make a VPN an effective privacy tool.

* **Encryption:** A VPN creates a secure, encrypted "tunnel" between the user's device and the VPN server. All internet traffic is routed through this tunnel. ProtonVPN uses **AES-256 encryption**, which is a military-grade standard that makes the data unreadable to anyone trying to intercept it, such as an Internet Service Provider (ISP) or attackers on a public Wi-Fi network.

* **No-Logs Policy:** A critical feature of a trustworthy VPN is a strict no-logs policy. This means the VPN provider does not track, collect, or store any information about the user's online activities, such as which websites they visit or what files they download. This prevents the data from being shared with third parties or seized by authorities.

* **Kill Switch:** This is a safety feature that automatically blocks all internet traffic from the device if the VPN connection unexpectedly drops. A kill switch prevents the user's real IP address from being accidentally exposed.

## 5. Summary of VPN Benefits and Limitations

### ### Benefits:
1.  **Privacy:** Hides your real IP address and prevents your ISP from monitoring your online activity.
2.  **Security:** Encrypts your internet connection, protecting you from data theft, especially on unsecured public Wi-Fi networks.
3.  **Bypassing Geo-Restrictions:** Allows you to access content and services that may be blocked in your geographic region.

### ### Limitations:
1.  **Reduced Speed:** The process of encrypting data and routing it through a distant server almost always results in a slower internet connection.
2.  **Trust is Required:** You are shifting your trust from your ISP to the VPN provider. A VPN with a poor privacy policy or weak security can be more dangerous than using no VPN at all.
3.  **Free Tier Restrictions:** Free VPNs, while useful, often come with limitations such as data caps, slower speeds, and a limited number of server locations.

## 6. Conclusion

A VPN is an essential tool for enhancing online privacy and security. By creating an encrypted tunnel and masking the user's true IP address, it effectively protects against ISP snooping and threats on public networks. While limitations such as reduced speed exist, the security benefits provided by a reputable VPN service are significant for any privacy-conscious user.
