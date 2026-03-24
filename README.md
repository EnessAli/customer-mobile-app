# depoin-customer

**Depoin** — A cross-platform Flutter e-commerce marketplace application for customers. Provides product discovery, cart management, vendor browsing, reviews, and real-time order tracking.

> The application code is maintained in a private repository. This repository serves as a public showcase.

## Features

| Module | Description |
|--------|-------------|
| **Home** | Personalized product feed and banner carousel |
| **Products** | Product detail pages with image gallery and specs |
| **Search** | Full-text product and vendor search |
| **Categories** | Hierarchical category browsing |
| **Vendors** | Vendor discovery, ratings, and storefronts |
| **Cart** | Persistent shopping cart with quantity management |
| **Orders** | Order history and real-time status tracking |
| **Reviews** | Star ratings and written product reviews |
| **Offers** | Flash deals and promotional listings |
| **Messaging** | In-app chat between customers and vendors |
| **Notifications** | Firebase push notifications |
| **Wishlist** | Save products for later |
| **Account** | User profile, addresses, and payment methods |
| **Auth** | Registration, login, and session management |
| **Onboarding** | First-run walkthrough with animated screens |

## Tech Stack

`Flutter` `Dart` `Riverpod` `GoRouter` `Dio` `Firebase`

## Key Dependencies

| Package | Purpose |
|---------|---------|
| `flutter_riverpod` | State management |
| `go_router` | Declarative routing |
| `dio` | HTTP client with interceptors |
| `firebase_core` + `firebase_messaging` | Push notifications |
| `flutter_local_notifications` | Local notification scheduling |
| `flutter_rating_bar` | Review star ratings |
| `carousel_slider` | Home page banner carousel |
| `lottie` | Animated onboarding illustrations |
| `share_plus` | Product sharing |
| `permission_handler` | Runtime permission requests |

## Architecture

Feature-first folder structure aligned with Clean Architecture principles.

```
lib/
  features/
    auth/
    onboarding/
    home/
    products/
    search/
    categories/
    vendors/
    cart/
    orders/
    reviews/
    offers/
    messaging/
    notifications/
    wishlist/
    account/
    legal/
  config/
  network/
  router/
  theme/
  utils/
```
