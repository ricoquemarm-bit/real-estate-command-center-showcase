# Real Estate Command Center — Portfolio Showcase

A sanitized portfolio case study for a property-sales operating system covering listings, buyer qualification, viewing coordination, offers, agent performance, follow-ups, and conversion reporting.

## Product preview

| Property command | Listings |
| --- | --- |
| ![Property command](screenshots/dashboard.png) | ![Listings](screenshots/listings.png) |
| Buyer pipeline | Viewing calendar |
| ![Buyer pipeline](screenshots/pipeline.png) | ![Viewing calendar](screenshots/viewings.png) |

![Portfolio reports](screenshots/reports.png)

```mermaid
flowchart LR
 A[Listing portfolio] --> B[Property command]
 C[Buyer leads] --> D[Qualification pipeline]
 B --> E[Viewing calendar]
 D --> E
 E --> F[Offers and negotiation]
 F --> G[Portfolio reporting]
```

Open `demo/index.html` for the safe static preview. The complete interactive source remains private. All properties, buyers, agents, prices, appointments, and performance values are fictional. No private address, contact detail, credential, document, or production API is included.

[Rico Integration](https://ricointegration.com/)
