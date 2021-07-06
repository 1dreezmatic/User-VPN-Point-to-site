# User-VPN-Point-to-site
So many obscurities on client-side configuration on Azure point-to-site configurations made clear.
This particular one is regarding how to set up the client side configuration so that the PC running a Linux OS can connect to an Azure VNET privately.
This was tested on Canonical Ubuntu 18.04 & 20.04.
If you are running a different distro, you can make the minor adjustments (concept remains same) where needed as I tried to annotate so anyone can follow along.

Ensure you have made the necessary configurations on the Azure portal using this guide till VPN tunnel type selection: https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-point-to-site-resource-manager-portal#tunneltype 
Ensure IKEv2 is selected.
