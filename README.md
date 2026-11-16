# Kitabi (كتابي)

**An Android app for buying and selling used books, person to person, with no middleman.**

تطبيق أندرويد لبيع وشراء الكتب المستعملة من شخص لشخص، بدون وسيط.

> Software Engineering team project · Team **BYA** · Section 101
> **Status:** Phase 1 (project proposal) submitted. Development starts in Sprint 1.

---

## The Problem

New books, printing, and ink are expensive for students and readers, while useful books sit unused on shelves once their owners no longer need them. Today people trade used books in scattered Facebook and WhatsApp groups, where posts are unorganized and hard to search. Buyers cannot find the book they need, and sellers do not reach the people looking for it.

## The Solution

Kitabi is an organized marketplace for used books. The seller sets the price, the buyer pays less than a new copy, and both sides talk directly. Books are found through categories, search, and filters instead of random scrolling.

## Core Features (MVP)

| # | Feature | Description |
|---|---------|-------------|
| 1 | Registration & Login | Create an account and sign in with email and password |
| 2 | Post a Listing | Add photos, title, category, price, condition, and area |
| 3 | Browse by Category | Home page with a scrollable category bar |
| 4 | Search & Filter | Search by title or author; filter by price, condition, and area |
| 5 | Contact via WhatsApp | One tap opens a WhatsApp chat with the seller |

### Planned if time permits

- Interests and a "Suggested for you" section
- Seller ratings and reporting
- Favorites and notifications
- Managing your own listings (edit, delete, mark as sold)

## Tech Stack

| Layer | Technology |
|-------|------------|
| App | Android (Native), Java |
| UI | XML layouts, Material Components |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore |
| Image storage | Supabase Storage |
| Testing | JUnit, Espresso |
| Version control | Git, GitHub |
| Project management | GitHub Projects |

## Architecture

```
User → Android App (Java) → Firebase Authentication   (login)
                          → Cloud Firestore            (users, listings, photo URLs)
                          → Supabase Storage           (book photos)
                          → WhatsApp                   (contact the seller)
```

## Timeline

| Sprint | Weeks | Focus |
|--------|-------|-------|
| 1 | 3 – 4 | Project setup, registration and login |
| 2 | 5 – 6 | Post a listing with photo upload |
| 3 | 7 – 8 | Home page, book details, categories |
| 4 | 9 – 10 | Search and filter, WhatsApp contact |
| 5 | 11 – 12 | Nice-to-have features and bug fixes |
| 6 | 13 – 14 | Final testing and presentation |

## Team BYA

| Name | Role | GitHub |
|------|------|--------|
| Yusuf Khaled Saleh | Product Owner | [@yosef-khaled04](https://github.com/yosef-khaled04) |
| Baraa Nidal Abu Taqiya | Scrum Master | [@BaraaNedal](https://github.com/BaraaNedal) |
| Abdelfattah Nader Hamdan | Developer | [@Abood-devv](https://github.com/Abood-devv) |

All members write code in every sprint.

## Documents

- [Phase 1: Project Idea Proposal](docs/Kitabi_Phase1_Project_Proposal.docx)

## Getting Started

Setup instructions will be added in Sprint 1, once the Android project is created.
