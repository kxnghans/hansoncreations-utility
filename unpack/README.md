# Unpack

Unpack is an all-in-one travel planning and packing application designed to streamline group trips, optimize credit card rewards, and organize itineraries without cloud lock-in.

## Core Pillars

### 1. Intelligent Planning & Itineraries
- **Mission Control Hub**: Timeline builder for flights, accommodations, excursions, and activities.
- **AI Travel Concierge**: Interactive conversational assistant for generating, editing, and scoping itineraries by day or activity with voice input support.
- **Waypoint Plotting**: Visual itinerary mapping with smooth timeline connectors.

### 2. Context-Aware Smart Packing
- **Dynamic Packing Lists**: Customized packing suggestions based on destination, trip duration, expected weather, and activities.
- **Categorization & Bag Weight**: Organized item sorting with luggage weight estimation to avoid airline baggage fees.

### 3. Financial Intelligence & Travel Rewards
- **Card Benefits Tracker**: Monitors lounge access (Priority Pass, Centurion), Global Entry/TSA PreCheck fee credits, and travel insurance coverage across major cards (Amex Platinum/Gold, Chase Sapphire Reserve/Preferred, Capital One Venture X).
- **Annual Credit Tracker**: Tracks recurring statement credits (dining, hotel, ride-share, entertainment).
- **Collaborative Savings**: Group travel savings goals with automated equal split calculators.
- **Trip Expense Budgeting**: Multi-currency expense logs.

### 4. Community & Travel Hacks
- **Shared Itineraries**: Browse, clone, and customize community travel guides.
- **Travel Hacks Catalog**: Master collection of travel strategies structured across Beginner, Intermediate, Expert, and Legend tiers.

## Design & Security Model

- **Tactile UI System**: Neumorphic depth, Skia glassmorphic blurs, and physics-based spring animations.
- **Tiered Zero-Knowledge Storage**:
  - **Tier 1 (Personal IDs & Passports)**: Passports, visas, driver's licenses, and health records are encrypted (AES-256) and saved **strictly on-device**. They never upload to cloud storage.
  - **Tier 2 (Tickets & Bookings)**: Flight tickets and hotel vouchers sync to an encrypted private Supabase vault with Row Level Security (RLS) for multi-device access on Pro accounts.
- **Local-First Reliability**: Local SQLite database with TanStack Query synchronization ensures total offline availability when traveling without cell service.

## Documentation & Links
- Web: [hansoncreations.com](https://hansoncreations.com)
- Bug Reports: [hansoncreations.com/bug-report](https://hansoncreations.com/bug-report)
- Privacy Policy: [PRIVACY.md](./PRIVACY.md)
- Root Hub: [HansOnCreations Utility Hub](../README.md)


