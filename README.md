# Coutureandcocktails

Official Luxury Event Ticketing & Verification Platform for Couture & Cocktails 2026.

## Overview
Couture & Cocktails is a luxury soirée and high-fashion ticketing platform built for Benin City, Edo State (December 28, 2026).

## Features
- **Real-Time Live Inventory & Ticketing:** Backed by Google Cloud Firestore database.
- **Paystack Payment Gateway:** Integrated inline card and bank checkout in Nigerian Naira (NGN).
- **Executive Command Center:** Real-time guest ledger, gate check-in scanner, live revenue metrics, and full frontend CMS.
- **Native Digital Passes:** Instant client-side scannable QR generation (via Canvas/QRious) with high-res PNG pass downloads.
- **Production Hardened:** Zero local storage leakage, Stored XSS sanitization, and strict Firestore Security Rules.

## Files
- `couture_cocktails_event_platform.html` — Main production single-file application.
- `firestore.rules` — Production Cloud Firestore security rules.
- `firebase.json` — Firebase CLI project configuration.
