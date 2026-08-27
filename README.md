# Awesome-Subscriptions

Edit
Top Subscription Management & Billing Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Subscription Management, Recurring Billing, Usage-Based Billing & Revenue Operations
Last updated: August 2026

This repository tracks notable SaaS/hosted platforms and open-source projects for Subscription Management & Billing. These tools help businesses manage recurring subscriptions, pricing plans, usage-based billing, invoicing, payments, renewals, dunning, entitlements, metering, and subscription analytics.

Examples include Chargebee, Recurly, Zuora, Maxio, Paddle, Stripe Billing, Billsby, ChargeOver, Sticky.io, and Appstle.

Open-source emphasis: This section is heavily expanded with open-source billing engines, metering platforms, subscription-management frameworks, payment infrastructure, and commerce platforms that can be self-hosted or used as building blocks for custom subscription systems. Notable projects include Kill Bill, Lago, OpenMeter, Medusa, Solidus, and related billing infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

Additional Strong Open-Source Options

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Chargebee
Subscription management and recurring billing platform supporting plans, invoicing, payments, revenue operations, and subscription analytics.

Recurly
Subscription management and recurring billing platform focused on subscription lifecycle management, payments, retention, and revenue optimization.

Zuora
Enterprise subscription management and monetization platform supporting recurring, usage-based, and hybrid business models.

Maxio
B2B SaaS billing and revenue management platform for subscription billing, usage-based pricing, renewals, and financial operations.

Paddle
Merchant-of-record and billing platform for SaaS companies, handling payments, subscriptions, taxes, invoicing, and global compliance.

Stripe Billing
Recurring and usage-based billing infrastructure integrated with the broader Stripe payments ecosystem.

Billsby
Subscription billing platform providing recurring billing, pricing models, invoicing, customer management, and payment integrations.

ChargeOver
Automated recurring billing and subscription management platform with invoicing, payment collection, dunning, and customer management.

Sticky.io
Subscription commerce and recurring revenue platform designed for managing subscription businesses, billing, payments, and customer lifecycle operations.

Appstle
Subscription management platform primarily focused on e-commerce and Shopify businesses, providing recurring subscriptions, customer portals, analytics, and retention tools.

Additional Notable SaaS / Hosted Platforms

Zuora Billing — Enterprise billing engine for complex recurring and usage-based monetization.

Stripe Revenue Billing — Billing infrastructure for recurring, usage-based, and hybrid pricing.

Ordway — Cloud billing and revenue automation platform.

Metronome — Usage-based billing and monetization infrastructure for modern software companies.

Orb — Usage-based billing and monetization platform.

Amberflo — Usage metering and usage-based monetization platform.

Moesif — API analytics and usage intelligence with capabilities useful for usage-based monetization.

Lago Cloud — Hosted version of the Lago open-source billing infrastructure.

OpenMeter Cloud — Hosted usage metering and billing infrastructure for AI, APIs, and developer products.

Kill Bill / Aviate — Open-source billing core with hosted and enterprise offerings.

Open-Source GitHub Projects

Kill Bill
Open-source subscription billing and payments platform supporting recurring and usage-based subscriptions, invoicing, payments, credits, dunning, multi-tenancy, and extensibility. Kill Bill is licensed under Apache 2.0.

Lago
Open-source metering and usage-based billing API supporting subscription, usage-based, and hybrid pricing, invoicing, prepaid credits, coupons, and payment integrations.

OpenMeter
Open-source real-time metering and billing platform for AI, APIs, and developer products, with usage metering, subscription management, usage limits, product catalogs, prepaid credits, and invoice generation.

Medusa
Open-source commerce platform that can be extended with subscription products, recurring commerce, payments, pricing, and custom billing workflows.

Solidus
Open-source Ruby commerce platform providing a foundation for custom subscription commerce, product catalogs, pricing, orders, payments, and recurring-commerce implementations.

Saleor
Open-source GraphQL commerce platform that can serve as a foundation for custom recurring-commerce and subscription implementations.

Spree Commerce
Open-source e-commerce framework with APIs and extensibility suitable for building custom subscription and recurring-commerce systems.

WooCommerce Subscriptions Ecosystem
Open-source WooCommerce foundation that can be extended with subscription functionality and recurring payment integrations.

FOSSBilling
Open-source billing and client-management platform designed for hosting and service businesses, including invoicing, payments, client management, and automated billing workflows.

InvoicePlane
Open-source invoicing application useful as a lightweight foundation for recurring invoicing and subscription-related workflows.

Additional Strong Open-Source Options

OpenMeter — Real-time usage metering, entitlements, and usage-based billing.

Lago — Developer-focused open-source billing API for hybrid and usage-based pricing.

Kill Bill — Full subscription billing and payment engine with extensible plugins.

FOSSBilling — Open-source client billing and invoicing infrastructure.

Medusa — Headless commerce infrastructure that can be extended for subscription commerce.

Solidus — Ruby-based open-source commerce foundation.

Saleor — Headless commerce foundation for custom subscription experiences.

Spree — Open-source commerce framework suitable for customized recurring-commerce implementations.

InvoicePlane — Lightweight open-source invoicing infrastructure.

Frameworks for building custom subscription platforms: Combine Lago or Kill Bill for subscription/billing logic, OpenMeter for real-time usage metering, Stripe/Adyen/PayPal integrations for payment processing, Medusa/Saleor/Solidus for commerce, and PostgreSQL + Kafka/Redpanda + ClickHouse for event processing and billing analytics.

A particularly strong open-source architecture for modern AI/SaaS products is OpenMeter → Lago → payment gateway → accounting system, with Kafka/Redpanda handling usage events and ClickHouse providing high-volume usage analytics. OpenMeter explicitly supports real-time usage aggregation and usage-based billing, while Lago provides the pricing, invoicing, and subscription layer.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Prefer actively maintained projects with a public repository.

Clearly distinguish between fully open-source, source-available, and commercial hosted offerings.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Subscription billing involves payments, taxation, accounting, and financial compliance; evaluate each platform according to your jurisdiction and business model.

Open-source projects may require additional engineering for production-grade security, reliability, taxation, payment processing, and compliance.

Some platforms listed above are broader commerce or billing infrastructure rather than complete Chargebee/Zuora-style subscription-management replacements.

Made for SaaS founders, product teams, finance teams, developers, and revenue operations professionals.
Let's make subscription management and billing more open, programmable, composable, and developer-friendly.
