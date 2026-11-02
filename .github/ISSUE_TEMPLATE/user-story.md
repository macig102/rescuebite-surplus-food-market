---
name: User Story
about: Create a new backlog item or user story for sprint tracking
title: '[US-XX]: <Short Descriptive Title>'
labels: ['user-story', 'sprint-1']
assignees: ''
---

## 👤 User Story Statement
- **As a:** [Customer / Verified Merchant / Courier / Platform Admin]
- **I can:** [Perform a specific capability or action]
- **So that:** [Achieve a tangible social impact or business value]

## 🎯 Target Domain Area & OpenAPI Endpoint
- **Epic / Feature:** [Merchant Governance / Surplus Package Management / Order Reservation / Courier Dispatch]
- **API Endpoint:** [e.g., `POST /orders`, `POST /deliveries/{id}/verify-qr`, `PATCH /admin/stores/{id}/approve`]

## ✅ Acceptance Criteria (Given / When / Then)
```gherkin
Given [Initial context, prerequisites, or state]
When [User, merchant, or courier executes the target operation]
Then [Expected HTTP status code, state transition, and response body payload]
```

## ⚠️ Edge Cases & Concurrency Errors
- [ ] 409 Conflict (Stock depletion / concurrent courier claim race)
- [ ] 409 Conflict (Delivery time window expired / invalid QR code)
- [ ] 403 Forbidden (Unapproved merchant attempting package creation)
- [ ] 400 Bad Request (Invalid parameters or missing delivery address)

## ⏱️ Initial Effort Estimate (Story Points)
- [ ] 1  [ ] 2  [ ] 3  [ ] 5  [ ] 8
