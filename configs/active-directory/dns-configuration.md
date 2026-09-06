# DNS Configuration

The Windows Server Domain Controller provides DNS services for the `cbc.lab` domain.

![Active Directory DNS Configuration](../../screenshots/AD_3.PNG)

Tailscale MagicDNS was configured to use the Domain Controller as the DNS server for the lab domain.

![Tailscale DNS Settings](../../screenshots/Tailscale_dns_seting.PNG)

This configuration allows domain-joined systems to resolve Active Directory hostnames and communicate with the Domain Controller across the Tailscale network.
