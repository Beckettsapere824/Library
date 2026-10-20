# VPN and VPS

Pricing checked on 2026-10-20. Provider prices, promotions, and country availability change; verify live checkout terms before purchase.

## VPN vs. VPS

A **VPN** is a protected network connection. A commercial VPN app typically encrypts traffic from a device to the provider’s VPN gateway; websites then see the gateway’s IP address. A **VPS** (virtual private server) is a virtual machine that rents compute, storage, and network resources. You manage its operating system and applications. A VPS can host a self-managed VPN, but it is not itself a commercial privacy VPN service. See the [NIST VPN definition](https://csrc.nist.gov/glossary/term/virtual_private_network) and [DigitalOcean Droplets](https://www.digitalocean.com/products/droplets).

Choose a commercial VPN when you want a provider-managed client, encrypted connection, and a choice of exit locations. Choose a VPS when you need an always-on server and control over the software running on it. A VPN does not make a person anonymous: accounts, cookies, device fingerprints, endpoint compromise, and the VPN provider’s own visibility still matter.

## ExpressVPN

**Official product:** [ExpressVPN](https://www.expressvpn.com/)

ExpressVPN is a consumer VPN service, not a VPS. It provides apps for Windows, macOS, Linux, iOS, Android, Apple TV, Android TV, and Fire TV, plus router and browser-extension support. The provider lists servers in 113 countries and unlimited VPN bandwidth; these are vendor specifications, not a personal speed guarantee. Its MediaStreamer Smart DNS feature works with some devices but does **not** encrypt their connection. See [downloads and network](https://www.expressvpn.com/vpn-download) and [supported devices](https://www.expressvpn.com/features/how-many-devices-can-i-connect).

**Security and privacy.** ExpressVPN says its policy does not log browsing history, traffic destinations or content, DNS queries, connection timestamps/duration, or assigned VPN IPs. It does collect account/payment information and limited service statistics, as described in its [privacy policy](https://www.expressvpn.com/privacy-policy). TrustedServer runs in RAM so data is cleared on reboot; Lightway is open source, and the Trust Center lists external audits. A no-logs policy does not equal absolute anonymity. See [Trust Center](https://www.expressvpn.com/trust).

**Price.** No free tier was advertised on the checked pricing page. A US-dollar 28-month introductory offer (two years plus four months) listed Basic at $2.99/month effective ($83.72 initial payment; then $99.95/year), Advanced at $4.49/month ($125.72 initial; then $119.95/year), and Express Pro at $7.49/month ($209.72 initial; then $199.95/year). Taxes may apply. The offer includes a 30-day money-back guarantee for eligible new purchases; app-store purchases follow store refund rules. Confirm the price, renewal, and guarantee in the checkout for your region. See [pricing](https://www.expressvpn.com/pricing) and [subscription details](https://www.expressvpn.com/support/manage-account/available-subscriptions/).

**Official references:** [Product](https://www.expressvpn.com/) · [Pricing](https://www.expressvpn.com/pricing) · [Downloads and network](https://www.expressvpn.com/vpn-download) · [Privacy policy](https://www.expressvpn.com/privacy-policy) · [Trust and audit reports](https://www.expressvpn.com/trust) · [Advanced Protection](https://www.expressvpn.com/features/advanced-protection)

## Proton VPN

**Official product:** [Proton VPN](https://protonvpn.com/)

Proton VPN is a consumer VPN service, not a VPS. Apps are available for Windows, macOS, Linux, Android, iOS/iPadOS, Chromebook, Android TV, and Apple TV, with Chrome and Firefox extensions. It supports WireGuard, OpenVPN, and IKEv2, and documents a kill switch and DNS-leak protection. Paid features include NetShield DNS filtering, Secure Core multi-hop, split tunnelling, and streaming support. See [features](https://protonvpn.com/features).

Proton says its apps are open source and independently audited, and that its no-logs policy has been audited. These are provider policy and audit claims, not a promise that websites, logged-in accounts, device fingerprinting, or a compromised device cannot identify a user. See the [no-logs policy](https://protonvpn.com/features/no-logs-policy).

**Free tier and price.** Proton Free is $0, requires no card, allows one device, has unlimited data, and lets Proton select servers in 10 countries. The pricing page labels the Free plan’s speed tier as “medium”; real-world performance depends on the connection and server load. VPN Plus was listed at $3.49/month on a 24-month introductory term ($83.76 billed initially), renewing at $83.88 per 12 months. This is term- and currency-dependent; confirm the checkout total and renewal price. See [pricing](https://protonvpn.com/pricing), [plan details](https://protonvpn.com/support/proton-vpn-plans), and [free vs. paid](https://protonvpn.com/free-vpn/free-vs-paid).

**Official references:** [Product and downloads](https://protonvpn.com/) · [Plans and pricing](https://protonvpn.com/pricing) · [Plan inclusions](https://protonvpn.com/support/proton-vpn-plans) · [Features](https://protonvpn.com/features) · [No-logs policy](https://protonvpn.com/features/no-logs-policy)

## VPS example: DigitalOcean Droplets

A Droplet is a DigitalOcean virtual machine. It can host a website, database, development environment, or self-managed VPN. The customer manages the OS, updates, firewall, credentials, applications, and data. Capacity and performance depend on the selected CPU, memory, storage, and plan. See the [Droplets overview and FAQ](https://www.digitalocean.com/products/droplets).

Bundled plans start at $4/month and include plan-dependent outbound transfer starting at 500 GiB/month. Extra outbound transfer is listed at $0.01/GiB. Billing varies by configuration; stopping a reserved Droplet does not end billing, so destroy it when it is no longer needed. DigitalOcean does not advertise a permanent free Droplet tier; new-user credits may be promotional and eligibility-limited. See [official billing details](https://docs.digitalocean.com/products/droplets/details/pricing/).

**Official references:** [Droplets](https://www.digitalocean.com/products/droplets) · [Droplet pricing and billing](https://docs.digitalocean.com/products/droplets/details/pricing/)
