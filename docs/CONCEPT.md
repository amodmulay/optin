# Optin: Concept Document

Status: draft v0.1. Items marked **Assumption** need confirmation.

## 1. Summary

Optin is a deals Progressive Web App (PWA) for the Indian and Turkish communities in Germany. It brings together offers from businesses these communities already use (grocery and spice stores, restaurants, sweet shops, remittance and telecom services, travel, events) in one installable, mobile-first app, available in the languages people actually speak.

## 2. Problem

- Deals for these communities are scattered across WhatsApp groups, Facebook pages, flyers and word of mouth.
- Mainstream German deal sites do not cover community-specific businesses and are not available in Hindi or Turkish.
- Community businesses, often small and family-run, have no affordable way to reach customers beyond their own neighbourhood.
- App store distribution and app development are out of reach for most of those businesses.

## 3. Target users

| Group | Who | Main need |
|---|---|---|
| Shoppers | Indian and Turkish residents, students, professionals and families in German cities | Find relevant, trustworthy deals nearby, in their language |
| Merchants | Community-focused stores, restaurants, service providers | Reach customers cheaply and see whether it works |
| Community organisers | Associations, event groups | Share offers and events with members |

**Assumption:** the first launch targets a small number of cities with large communities rather than all of Germany.

## 4. Value proposition

- **For shoppers:** one place for relevant deals, filtered by city, category and community, with no account needed to browse.
- **For merchants:** a simple way to post offers and reach local customers without building an app.
- **For both:** multilingual (German, English, Hindi, Turkish) and installable from the browser.

## 5. Core features (MVP candidates)

1. Browse and search deals by city, category and distance.
2. Deal detail page with validity dates, terms, location and a way to redeem (code, link or show-in-store).
3. Language switcher: German, English, Hindi, Turkish.
4. Save favourites and get alerts for chosen categories or cities.
5. Merchant submission flow with moderation before publishing.
6. Report a deal (expired, wrong, misleading).
7. Installable PWA with offline access to saved deals.

Later: user accounts and personalisation, merchant dashboard with basic analytics, community event listings, loyalty or coupon wallet, push notifications.

## 6. Why a PWA

- No app store gatekeeping, review delays or fees.
- One codebase for phones and desktop.
- Shareable links fit how the communities already share deals (WhatsApp, social media).
- Installable and capable of offline use and push notifications on current browsers.

Trade-off: push notification and install behaviour differ between iOS and Android, so this needs testing early.

## 7. Content and trust

- Every deal shows its source, validity period and when it was last verified.
- New merchants are moderated before their first deal goes live.
- Users can report bad deals; reported deals are reviewed quickly.
- Sponsored or paid placements, if any, are clearly labelled.

## 8. Business model (options to decide)

| Option | Notes |
|---|---|
| Free listings, paid featured placement | Low barrier for merchants; revenue depends on traffic |
| Affiliate commissions on partner offers | Needs clear disclosure to users |
| Subscription for merchants (analytics, scheduling) | Later stage |

**Assumption:** start free for merchants to build supply, and add monetisation after traction.

## 9. Legal and compliance (Germany/EU)

To be reviewed with a qualified adviser before launch.

- **GDPR:** consent for analytics and notifications, privacy policy, data minimisation, a way to delete data.
- **Impressum:** a legal notice is required for commercial German websites.
- **Advertising rules:** paid and affiliate content must be clearly marked as advertising.
- **Consumer protection:** deals must not be misleading about price or availability.
- **Cookies and storage:** consent where required for non-essential tracking.

## 10. Success measures

- Active deals per city.
- Number of onboarded merchants.
- Weekly active users and install rate.
- Return visits and saved-deal usage.
- Redemption or click-through per deal.
- Share of deals reported as wrong or expired (quality).

## 11. Risks

| Risk | Mitigation |
|---|---|
| Not enough deals at launch (cold start) | Seed with a few partner merchants in one city; manual curation |
| Stale or wrong deals erode trust | Expiry dates required; reporting; verification timestamps |
| Low push adoption on iOS | Do not rely on push alone; add email or WhatsApp-share flows |
| Moderation workload | Start small; lightweight admin tooling |
| Legal missteps on advertising or data | Early legal review; clear labelling |

## 12. Open questions

1. Which cities launch first?
2. Is the build plan's tech stack decided (framework, backend, hosting)?
3. Are user accounts required in v1, or is browsing anonymous?
4. Who moderates deals, and how many hours a week is realistic?
5. How are deals sourced initially: manual entry, merchant self-service, or both?
6. Which languages are required at launch versus later?
7. What is the app's brand name and visual identity?

## 13. Next steps

1. Confirm the assumptions and answer the open questions above.
2. Merge in the detailed build plan and phase it.
3. Turn each phase into GitHub issues.
