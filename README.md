# Awesome-B2B-E-Commerce-Billing

# Awesome-B2B-E-Commerce-Billing

**Top B2B E Commerce Billing (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on B2B Storefronts, Quote-to-Cash, Subscription Billing & ERP-Integrated Commerce*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **B2B E-Commerce & Billing**. These tools enable manufacturers, distributors, and wholesalers to run B2B storefronts with company accounts, negotiated pricing, quotes, and net terms—from fully managed enterprise platforms with ERP integration and native B2B billing to open-source commerce and billing engines that give organizations complete control over their quote-to-cash workflows.



**Examples** include Shopify Plus, BigCommerce B2B Edition, HubSpot Commerce Hub, OroCommerce, Sana Commerce, NuORDER, Pepperi, Stripe Billing, Chargebee, and Zuora (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted B2B commerce, billing, and open infrastructure. **Critical note**: The open-source landscape splits into two categories—**B2B commerce platforms** (GrandNode, Spree) with storefronts and B2B pricing, and **billing engines** (UniBee) for subscription and invoice management. No open-source project matches OroCommerce's ERP-native depth or Shopify Plus's unlimited B2B catalogs out of the box.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Shopify Plus](https://www.shopify.com/plus)**

  **Enterprise commerce platform with native B2B capabilities**. B2B features include company profiles, up to **three active catalogs** on lower plans, unlimited catalogs on Plus, payment terms (net terms), volume pricing, and vaulted payments. Plus adds direct catalog assignment to individual companies for true customer-specific pricing at scale . **Pricing**: **$2,300/month** or 0.4% of monthly revenue (whichever is higher), capped around $40,000/month . **Free tier**: None. **Best for**: mid-market to enterprise merchants hitting catalog limits on lower plans or needing unlimited B2B catalogs—**trade-off**: multi-level approvals and formal RFQ workflows are not native and require custom development .



- **[BigCommerce B2B Edition](https://www.bigcommerce.com/)**

  **All-in-one B2B solution** integrated into the BigCommerce control panel. Adds company accounts, sales quotes with negotiated pricing, invoice management for purchase orders on net terms, user roles, sales agents, and a **Buyer Portal** for self-service purchasing workflows . **Pricing**: BigCommerce plans from **$39/month (Core)** to **$399/month (Scale)**; B2B Edition provisioned via app and support request . **Free tier**: Trial available. **Best for**: mid-market B2B brands wanting native B2B features without Shopify Plus pricing—**trade-off**: B2B Edition requires provisioning; not self-serve.



- **[HubSpot Commerce Hub](https://www.hubspot.com/products/commerce)**

  **CPQ, invoicing, and payments** on the HubSpot platform. Professional ($85/seat/month) adds quotes, e-signature (25/user/month), tiered pricing, and automated sales tax. Enterprise ($140/seat/month) adds advanced approvals and 50 signatures/user/month. Payment processing: **2.9% + $0.5% platform fee** for HubSpot Payments; or keep Stripe with **0.75% platform fee** . **Free tier**: Yes, basic invoices and payment links. **Best for**: HubSpot CRM users wanting quote-to-cash without leaving the platform—**trade-off**: not a full storefront; commerce is quote and invoice-centric.



- **[OroCommerce](https://oroinc.com/b2b-ecommerce/)**

  **Enterprise B2B commerce platform** built for manufacturers, distributors, and wholesalers. Handles **8 million+ SKUs**, hundreds of millions of prices, and tens of thousands of orders per hour. Features segmentation engine, AI-powered search, **OroPay** (native payments with Global Payments), customer invoicing portal, and native integrations with SAP, NetSuite, Microsoft Dynamics, and Epicor . **Pricing**: Quote-only. **Free tier**: None. **Best for**: complex B2B operations needing ERP-native pricing, invoicing, and scale—**trade-off**: enterprise implementation commitment.



- **[Sana Commerce](https://www.sana-commerce.com/)**

  **ERP-integrated B2B e-commerce** for manufacturers and distributors. Direct ERP connection means real-time product, pricing, and stock data without sync overhead. Features include ordering by customer's own article numbers, guided product finder, and real-time inventory visibility across warehouses . **Pricing**: Quote-only. **Free tier**: None. **Best for**: Microsoft Dynamics and SAP ERP customers wanting a storefront that mirrors ERP data in real time—**trade-off**: ERP-centric; less flexible for non-ERP-driven pricing.



- **[NuORDER by Lightspeed](https://www.nuorder.com/)**

  **B2B eCommerce for wholesale fashion and retail**. Brands and retailers browse catalogs, access real-time inventory, and place orders via desktop or mobile app. Mobile app supports offline order creation, barcode scanning, and buyer signatures. AI features for buying intelligence and assortment planning . **Pricing**: Quote-only. **Free tier**: None. **Best for**: fashion and lifestyle brands selling wholesale to retailers—**trade-off**: vertical-specific; not a general B2B platform.



- **[Pepperi](https://www.pepperi.com/)**

  **Unified B2B commerce platform** for consumer goods manufacturers, distributors, and wholesalers. Combines B2B eCommerce storefront, Sales Force Automation, Retail Execution, Direct Store Delivery (DSD), and Trade Promotions. Route accounting app for iOS/Android supports van sales and offline order placement . **Pricing**: Quote-only. **Free tier**: None. **Best for**: consumer goods teams needing field sales and DSD alongside B2B ordering—**trade-off**: training investment required to maximize value.



- **[Stripe Billing](https://stripe.com/billing)**

  **Subscription and invoice billing** infrastructure. Handles recurring billing, invoicing, revenue recognition, and payment collection for B2B subscription models. **Pricing**: Usage-based; percentage of billing volume. **Free tier**: None for Billing. **Best for**: SaaS and subscription B2B businesses wanting billing without a full commerce platform.



- **[Chargebee](https://www.chargebee.com/)**

  **Subscription management and billing** for SaaS and recurring revenue businesses. **Pricing**: Quote-only; tiered by revenue. **Free tier**: Trial available. **Best for**: subscription B2B companies needing dunning, revenue recognition, and plan management.



- **[Zuora](https://www.zuora.com/)**

  **Enterprise subscription billing and monetization** platform. **Pricing**: Quote-only. **Free tier**: None. **Best for**: large enterprises with complex subscription and usage-based billing models.



## Open-Source GitHub Projects



- **[GrandNode](https://github.com/grandnode/grandnode2)**

  **Open-source e-commerce platform for .NET** (license per repo) — **the strongest open-source B2B storefront for .NET teams**, with native B2B features on a self-hosted stack . **Features**: **B2B and B2C from the same catalog**; **customer groups, tier prices, sales employees** for B2B workflows; **multi-store** and **multi-vendor marketplace**; **payments** via Stripe Checkout, Braintree, cash on delivery, and plugins; **REST API** for headless storefronts and ERP/PIM/CRM integration; Docker and Kubernetes deployment . **Tech stack**: ASP.NET Core 10, C#, MongoDB, Vue 3. **Deploy**: Self-hosted (Docker images on Docker Hub and GHCR) . **Trade-off**: **.NET ecosystem lock-in**—best for C#/.NET teams. MongoDB dependency. No native quote-to-cash workflow or invoice management; billing is payment-oriented, not subscription-grade. **Best for**: .NET development teams wanting a self-hosted B2B commerce platform with tier pricing, multi-store, and headless API capabilities.



- **[Spree Commerce](https://github.com/spree/spree)**

  **Open-source B2B commerce platform** (AGPL-3.0 for Community) — **the most battle-tested open-source B2B storefront**, validated by Maisonette (65,000+ products, hundreds of brands). **Features**: **B2B wholesale portal** with spreadsheet-style grid ordering and customer-specific pricing at checkout; **Price Lists** for custom pricing by buyer organization; **multi-vendor marketplace module**; **Enterprise Edition** adds buyer organizations with spending limits and role-based purchasing. **Tech stack**: Ruby on Rails. **Deploy**: Self-hosted (Docker-first; no Redis required in 5.6). **Trade-off**: **Full platform adoption**; billing is payment-integration-based, not native subscription/invoice management. **Best for**: B2B distributors wanting a proven open-source storefront with wholesale pricing and payment integration.



- **[UniBee](https://github.com/UniBee-Billing/unibee)**

  **Open-source universal billing software for SaaS businesses** (AGPLv3) — **the most complete open-source billing engine** for subscription and invoice management, positioned as a free alternative to Chargebee, Recurly, and Paddle . **Features**: **Subscription management** (create, update, cancel); **invoicing** with automatic generation and sending; **billable metrics** tracking; **product and plan management**; **webhooks** for real-time events; **user management** with permissions; **reports** for business performance; **transaction management** including refunds; **discounts**; user portal or API integration . **Tech stack**: Docker, PostgreSQL, Redis (per deployment instructions). **Deploy**: Self-hosted (`docker-compose up`) or UniBee Cloud (paid SaaS) . **Trade-off**: **SaaS billing-focused**—not a B2B commerce storefront. No product catalog, checkout, or order management for physical goods. **Best for**: SaaS and subscription businesses wanting a self-hosted billing engine without commercial licensing—especially teams migrating from WooCommerce, WHMCS, or KillBill .



### Additional Strong Open-Source Options



- **Medusa** — Open-source headless commerce (MIT). Modular architecture; B2B features require custom development. **Best for**: developers wanting a TypeScript foundation to build B2B workflows.

- **Vendure** — TypeScript-native headless commerce (GPLv3). Plugin-first architecture; B2B pricing and approvals require Vendure Platform (commercial). **Best for**: teams wanting GraphQL-native commerce with plugin extensibility.

- **Saleor** — GraphQL-first headless commerce (BSD-3-Clause). Mature API; B2B features require custom apps. **Best for**: teams wanting a GraphQL-native backend.



**Frameworks for building custom systems**: Combine **GrandNode** or **Spree** as the B2B storefront with **UniBee** for subscription billing, and a payment processor (Stripe, Adyen) for transaction processing—creating a B2B e-commerce and billing stack. **None of these match OroCommerce's ERP-native quote-to-cash depth or Shopify Plus's unlimited B2B catalogs**; those require commercial platforms or significant custom development.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- B2B commerce and billing platforms handling financial data and transactions must comply with PCI DSS, data protection regulations (GDPR, CCPA, etc.), and tax regulations.

- **The "B2B commerce platform" vs. "billing engine" distinction is critical.** **Shopify Plus, BigCommerce B2B, OroCommerce, Sana, NuORDER, and Pepperi** are **commerce platforms**—they provide storefronts, catalogs, and B2B purchasing workflows. **HubSpot Commerce Hub** is **quote-to-cash**—it handles quotes, invoices, and payments but not a product storefront. **Stripe Billing, Chargebee, and Zuora** are **billing engines**—they manage subscriptions and invoices, not commerce. **UniBee** is an **open-source billing engine**. **GrandNode and Spree** are **open-source commerce platforms**. **No single open-source project covers both B2B storefront and subscription billing end-to-end.**

- **Shopify Plus's B2B catalog limits are a key decision point.** Lower Shopify plans now include up to three B2B catalogs; **Plus unlocks unlimited catalogs** for customer-specific pricing at scale . **If you have more than a handful of differently priced accounts, Plus is the practical threshold.**

- **BigCommerce B2B Edition is provisioned via app and support request**, not self-serve . **Factor provisioning time into your evaluation.**

- **OroCommerce and Sana Commerce are ERP-native platforms**—their value depends on your ERP (SAP, NetSuite, Dynamics). **If you are not ERP-centric, their differentiation is reduced.**

- **NuORDER and Pepperi are vertical-specific**—fashion/wholesale and consumer goods/DSD respectively. **They are not general-purpose B2B platforms.**

- **UniBee is the only mature open-source billing engine** in this list, explicitly positioned as a Chargebee/Recurly alternative . **The trade-off**: it is SaaS subscription billing, not B2B commerce with catalogs and orders.

- **Pricing opacity varies.** Shopify Plus publishes $2,300/month minimum . BigCommerce publishes plan tiers . HubSpot publishes per-seat pricing . OroCommerce, Sana, NuORDER, Pepperi, Chargebee, and Zuora require sales contact. **Validate with direct vendor conversations against your catalog complexity and billing volume.**

- Self-hosted open-source solutions require proper infrastructure, payment processor integration, PCI compliance (if handling card data), and ongoing maintenance. **B2B financial data is sensitive**—ensure your deployment meets all applicable security and compliance requirements before processing live transactions.



---



**Made for developers, B2B merchants, and organizations building transparent commerce and billing solutions.**

Let's make B2B E-Commerce & Billing more open, data-driven, and quote-to-cash friendly.
