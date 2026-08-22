# eBay (ebay)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

eBay is a multinational e-commerce corporation that operates a website facilitating consumer-to-consumer and business-to-consumer sales through its online platform. Users can buy and sell a wide range of products, including electronics, fashion, collectibles, and more, in an auction-style or buy-it-now format. eBay provides a secure and user-friendly platform for sellers to reach a global audience and for buyers to access a vast selection of items.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ebay/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Auctions, Commerce, Products, Marketplace

## Timestamps

- **Created:** 2023-11-09
- **Modified:** 2026-04-28

## APIs

### eBay Account API
The eBay Account API allows sellers to programmatically configure their seller accounts on eBay, including payment policies, return policies, fulfillment policies, sales tax tables, and program opt-ins.

**Human URL:** [https://developer.ebay.com/api-docs/sell/account/static/overview.html](https://developer.ebay.com/api-docs/sell/account/static/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Account

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/account/static/overview.html)
- [OpenAPI](openapi/ebay-account-openapi-original.yml)

### eBay Analytics API
The eBay Analytics API provides sellers with key performance metrics, traffic reports, customer service metrics, and seller standards information so they can measure and improve their performance on eBay.

**Human URL:** [https://developer.ebay.com/api-docs/sell/analytics/static/overview.html](https://developer.ebay.com/api-docs/sell/analytics/static/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Analytics

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/analytics/static/overview.html)
- [OpenAPI](openapi/ebay-analytics-openapi-original.yml)

### eBay Compliance API
The eBay Compliance API surfaces listing-violation and policy-compliance issues so sellers can identify and resolve listings that conflict with eBay marketplace policies.

**Human URL:** [https://developer.ebay.com/api-docs/sell/compliance/resources/methods](https://developer.ebay.com/api-docs/sell/compliance/resources/methods)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Compliance

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/compliance/resources/methods)
- [OpenAPI](openapi/ebay-compliance-openapi-original.yml)

### eBay Feed API
The eBay Feed API lets developers download large bulk feed files of eBay item, product, and order data for offline analysis and synchronization.

**Human URL:** [https://developer.ebay.com/api-docs/sell/feed/resources/methods](https://developer.ebay.com/api-docs/sell/feed/resources/methods)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Feed

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/feed/resources/methods)
- [OpenAPI](openapi/ebay-feed-openapi-original.yml)

### eBay Browse API
The eBay Browse API enables buyers to search and browse the eBay catalog, retrieve item details, and discover items by aspect or category.

**Human URL:** [https://developer.ebay.com/api-docs/buy/browse/overview.html](https://developer.ebay.com/api-docs/buy/browse/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Buy, Browse, Search

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/buy/browse/overview.html)
- [OpenAPI](openapi/ebay-browse-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/buy/browse/release-notes.html)

### eBay Deal API
The eBay Deal API exposes the deals and promotions surfaced on eBay's deal pages so applications can present discounted offers to shoppers.

**Human URL:** [https://developer.ebay.com/api-docs/buy/deal/resources/methods](https://developer.ebay.com/api-docs/buy/deal/resources/methods)

**Base URL:** https://api.ebay.com

#### Tags: Buy, Deals

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/buy/deal/resources/methods)
- [OpenAPI](openapi/ebay-deal-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/buy/deal/release-notes.html)

### eBay Marketing API
The eBay Marketing API provides merchandising placements, "also viewed" recommendations, and similar item suggestions to drive buyer engagement.

**Human URL:** [https://developer.ebay.com/api-docs/buy/marketing/resources/methods](https://developer.ebay.com/api-docs/buy/marketing/resources/methods)

**Base URL:** https://api.ebay.com

#### Tags: Buy, Marketing

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/buy/marketing/resources/methods)
- [OpenAPI](openapi/ebay-market-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/buy/marketing/release-notes.html)

### eBay Marketplace Insights API
The eBay Marketplace Insights API gives access to historical sold-item data across the eBay marketplace so applications can analyze pricing trends and sell-through rates.

**Human URL:** [https://developer.ebay.com/api-docs/buy/marketplace-insights/resources/methods](https://developer.ebay.com/api-docs/buy/marketplace-insights/resources/methods)

**Base URL:** https://api.ebay.com

#### Tags: Buy, Insights, Analytics

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/buy/marketplace-insights/resources/methods)
- [OpenAPI](openapi/ebay-marketplace-insights-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/buy/marketplace-insights/release-notes.html)

### eBay Offer API
The eBay Offer API supports the offers experience for buyers, allowing applications to discover and act on offers across eligible listings.

**Human URL:** [https://developer.ebay.com/api-docs/buy/offer/overview.html](https://developer.ebay.com/api-docs/buy/offer/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Buy, Offers

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/buy/offer/overview.html)
- [OpenAPI](openapi/ebay-offer-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/buy/offer/release-notes.html)

### eBay Order API
The eBay Order API enables buyer-side checkout and order management workflows, including guest checkout sessions and order retrieval.

**Human URL:** [https://developer.ebay.com/api-docs/buy/order/overview.html](https://developer.ebay.com/api-docs/buy/order/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Buy, Orders, Checkout

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/buy/order/overview.html)
- [OpenAPI](openapi/ebay-order-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/buy/order/release-notes.html)

### eBay Finances API
The eBay Finances API gives sellers programmatic access to payouts, transactions, transfers, and seller funds tied to managed payments.

**Human URL:** [https://developer.ebay.com/api-docs/sell/finances/overview.html](https://developer.ebay.com/api-docs/sell/finances/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Finances, Payments

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/finances/overview.html)
- [OpenAPI](openapi/ebay-finances-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/finances/release-notes.html)

### eBay Fulfillment API
The eBay Fulfillment API helps sellers manage post-purchase order fulfillment, shipments, tracking, and refunds.

**Human URL:** [https://developer.ebay.com/api-docs/sell/fulfillment/overview.html](https://developer.ebay.com/api-docs/sell/fulfillment/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Fulfillment, Orders

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/fulfillment/overview.html)
- [OpenAPI](openapi/ebay-fulfillment-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/fulfillment/release-notes.html)

### eBay Inventory API
The eBay Inventory API allows sellers to manage inventory items, offers, and listing publication on the eBay marketplace.

**Human URL:** [https://developer.ebay.com/api-docs/sell/inventory/overview.html](https://developer.ebay.com/api-docs/sell/inventory/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Inventory, Listings

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/inventory/overview.html)
- [OpenAPI](openapi/ebay-inventory-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/inventory/release-notes.html)

### eBay Logistics API
The eBay Logistics API provides shipping rate quotes and label purchasing for sellers fulfilling orders inside or outside the eBay platform.

**Human URL:** [https://developer.ebay.com/api-docs/sell/logistics/overview.html](https://developer.ebay.com/api-docs/sell/logistics/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Logistics, Shipping

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/logistics/overview.html)
- [OpenAPI](openapi/ebay-logistics-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/logistics/release-notes.html)

### eBay Metadata API
The eBay Metadata API exposes marketplace policies and configuration metadata that govern selling activity across countries and categories.

**Human URL:** [https://developer.ebay.com/api-docs/sell/metadata/overview.html](https://developer.ebay.com/api-docs/sell/metadata/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Metadata

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/metadata/overview.html)
- [OpenAPI](openapi/ebay-metadata-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/metadata/release-notes.html)

### eBay Negotiation API
The eBay Negotiation API lets sellers send targeted offers to interested buyers with discounted pricing on eligible listings.

**Human URL:** [https://developer.ebay.com/api-docs/sell/negotiation/overview.html](https://developer.ebay.com/api-docs/sell/negotiation/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Negotiation, Offers

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/negotiation/overview.html)
- [OpenAPI](openapi/ebay-negotiation-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/negotiation/release-notes.html)

### eBay Recommendation API
The eBay Recommendation API surfaces actionable recommendations sellers can apply to improve listing performance, such as enabling Promoted Listings.

**Human URL:** [https://developer.ebay.com/api-docs/sell/recommendation/overview.html](https://developer.ebay.com/api-docs/sell/recommendation/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Recommendations

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/recommendation/overview.html)
- [OpenAPI](openapi/ebay-recommendation-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/recommendation/release-notes.html)

### eBay Stores API
The eBay Stores API lets sellers manage the categories that organize listings within their eBay Store storefront.

**Human URL:** [https://developer.ebay.com/api-docs/sell/stores/overview.html](https://developer.ebay.com/api-docs/sell/stores/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Sell, Stores

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/sell/stores/overview.html)
- [OpenAPI](openapi/ebay-stores-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/sell/stores/release-notes.html)

### eBay Catalog API
The eBay Catalog API gives access to the eBay product catalog so sellers can attach items to canonical product entries when listing.

**Human URL:** [https://developer.ebay.com/api-docs/commerce/catalog/resources/methods](https://developer.ebay.com/api-docs/commerce/catalog/resources/methods)

**Base URL:** https://api.ebay.com

#### Tags: Commerce, Catalog, Products

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/commerce/catalog/resources/methods)
- [OpenAPI](openapi/ebay-catalog-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/commerce/catalog/release-notes.html)

### eBay Charity API
The eBay Charity API exposes the registered charitable organizations supported by eBay for Charity so applications can search and reference them.

**Human URL:** [https://developer.ebay.com/api-docs/commerce/charity/overview.html](https://developer.ebay.com/api-docs/commerce/charity/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Commerce, Charity

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/commerce/charity/overview.html)
- [OpenAPI](openapi/ebay-charity-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/commerce/charity/release-notes.html)

### eBay Identity API
The eBay Identity API returns information about the authenticated eBay user so applications can personalize the buying or selling experience.

**Human URL:** [https://developer.ebay.com/api-docs/commerce/identity/overview.html](https://developer.ebay.com/api-docs/commerce/identity/overview.html)

**Base URL:** https://apiz.ebay.com

#### Tags: Commerce, Identity

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/commerce/identity/overview.html)
- [OpenAPI](openapi/ebay-identity-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/commerce/identity/release-notes.html)

### eBay Media API
The eBay Media API allows sellers to upload and manage video assets that can be associated with their listings.

**Human URL:** [https://developer.ebay.com/api-docs/commerce/media/overview.html](https://developer.ebay.com/api-docs/commerce/media/overview.html)

**Base URL:** https://apim.ebay.com

#### Tags: Commerce, Media, Video

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/commerce/media/overview.html)
- [OpenAPI](openapi/ebay-media-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/commerce/media/release-notes.html)

### eBay Notification API
The eBay Notification API manages destinations and subscriptions for the event-driven notifications eBay publishes to integrators, including marketplace account deletion, item availability, item price, campaign budget status, and authorization revocation events.

**Human URL:** [https://developer.ebay.com/api-docs/commerce/notification/overview.html](https://developer.ebay.com/api-docs/commerce/notification/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Commerce, Notifications, Events

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/commerce/notification/overview.html)
- [OpenAPI](openapi/ebay-notification-openapi-original.yml)
- [AsyncAPI](openapi/ebay-priority-listing-revisions-asyncapi-original.yml)
- [AsyncAPI](openapi/ebay-market-account-deletion-asyncapi-original.yml)
- [AsyncAPI](openapi/ebay-item-price-asyncapi-original.yml)
- [AsyncAPI](openapi/ebay-item-availability-asyncapi-original.yml)
- [AsyncAPI](openapi/ebay-campaign-budget-status-asyncapi-original.yml)
- [AsyncAPI](openapi/ebay-authorization-revocation-asyncapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/commerce/notification/release-notes.html)

### eBay Taxonomy API
The eBay Taxonomy API exposes the category trees and item-aspect metadata that govern how items are classified across eBay marketplaces.

**Human URL:** [https://developer.ebay.com/api-docs/commerce/taxonomy/overview.html](https://developer.ebay.com/api-docs/commerce/taxonomy/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Commerce, Taxonomy, Categories

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/commerce/taxonomy/overview.html)
- [OpenAPI](openapi/ebay-taxonomy-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/commerce/taxonomy/release-notes.html)

### eBay Translation API
The eBay Translation API provides machine translation of seller-supplied content such as listing titles and descriptions into supported eBay marketplace languages.

**Human URL:** [https://developer.ebay.com/api-docs/commerce/translation/overview.html](https://developer.ebay.com/api-docs/commerce/translation/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Commerce, Translation, Localization

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/commerce/translation/overview.html)
- [OpenAPI](openapi/ebay-translation-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/commerce/translation/release-notes.html)

### eBay Client Registration API
The eBay Client Registration API enables developers to create the application keys (App ID, Cert ID, Dev ID) used to authenticate calls to eBay APIs.

**Human URL:** [https://developer.ebay.com/api-docs/developer/client-registration/overview.html](https://developer.ebay.com/api-docs/developer/client-registration/overview.html)

**Base URL:** https://api.ebay.com

#### Tags: Developer, Registration, Authentication

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/developer/client-registration/overview.html)
- [OpenAPI](openapi/ebay-client-registration-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/developer/client-registration/release-notes.html)

### eBay Key Management API
The eBay Key Management API manages the public/private key pairs developers use to sign requests for sensitive operations on the eBay platform.

**Human URL:** [https://developer.ebay.com/api-docs/developer/key-management/overview.html](https://developer.ebay.com/api-docs/developer/key-management/overview.html)

**Base URL:** https://apiz.ebay.com

#### Tags: Developer, Keys, Security

#### Properties
- [Documentation](https://developer.ebay.com/api-docs/developer/key-management/overview.html)
- [OpenAPI](openapi/ebay-key-management-openapi-original.yml)
- [Release Notes](https://developer.ebay.com/api-docs/developer/key-management/release-notes.html)

## Common Properties

- [Developer Portal](https://developer.ebay.com/)
- [Getting Started](https://developer.ebay.com/develop/get-started)
- [Guides](https://developer.ebay.com/develop/guides)
- [Tools](https://developer.ebay.com/develop/tools)
- [SDKs](https://developer.ebay.com/develop/ebay-sdks)
- [Widgets](https://developer.ebay.com/develop/widgets)
- [Support](https://developer.ebay.com/my/support/tickets)
- [Rate Limits](https://developer.ebay.com/develop/apis/api-call-limits)
- [Status](https://developer.ebay.com/support/api-status)
- [Forum](https://community.ebay.com/t5/Developer-Groups/ct-p/developergroup)
- [License](https://developer.ebay.com/join/api-license-agreement)
- [FAQ](https://developer.ebay.com/support/faq)
- [Blog](https://developer.ebay.com/updates/blog)
- [Newsletter](https://developer.ebay.com/updates/newsletter)
- [Events](https://developer.ebay.com/grow/events)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
