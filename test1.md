# Business Model Canvas — Iteration 3 (UQ Eats)

_Refined from Iteration 2, mapped to Test Cards H5–H8, H9–H12_

---

## 1. Customer Segments

**CS1 – Time-poor UQ students**  
UQ students with tight class windows (especially 12:00–14:00, back-to-back) who want predictable pickup and minimal queueing.  
- **Status:** Accepted  
- **Trace:** i1 H1/H2 → i2 H5/H6 → i3 H11/H12 (test_cards_v2.md)


**CS2 – International / multi-language students**  
Students who prefer to view menus and key actions in their preferred language, and need clear tags for allergens, spice, and dietary needs.  
- **Status:** Refined in i3  
- **Trace:** i1 H3 → i2 H7 → i3 H9/H10

**CS3 – Campus restaurants (later)**  
Campus merchants who want smoother peaks and fewer counter errors.  
- **Status:** De-prioritised for user-side MVP; insights logged  
- **Trace:** i1 H4 (logged as findings in i2)

---

## 2. Value Propositions

### For Students

**VP1 – Queue avoidance & predictable timing**  
Pre-order with both **Pick Time** and **Wait Time** options plus a visible “Expected Wait”, so students can fit orders between classes.  
- **Status:** Refined in i3  
- **Trace:** H5 → H11

**VP2 – Low-friction pickup with clear codes**  
“Ready” alerts include stall info, landmark, and a unique pickup code so orders can be collected without extra help.  
- **Status:** Refined in i3  
- **Trace:** H6 → H12

**VP3 – Safe & understandable menus for diverse users**  
Multi-language UI (language selector), translated labels, and clear allergen/spice/dietary tags reduce confusion and mistakes.  
- **Status:** Refined in i3  
- **Trace:** H7 → H9/H10

**VP4 – Simple flow, less thinking**  
Flat restaurant list and simple navigation, so students can move from “see restaurant” to “place order” in very few steps.  
- **Status:** Accepted  
- **Trace:** H8 (kept stable in i3)

### For Merchants (future)

**VP5 – Peak smoothing & fewer counter errors**  
Digital pre-orders and pickup slots reduce front-counter congestion and miscommunication.  
- **Status:** Concept kept; validation postponed  
- **Trace:** H5/H6 (merchant-side still future)

---

## 3. Channels

**CH1 – Mobile-friendly web app**  
Main channel for browsing, pre-ordering, choosing languages, and picking times.

**CH2 – QR codes at campus outlets**  
QR mini-flows at tables and counters to open UQ Eats on the spot.

**CH3 – On-campus posters & social media**  
Simple messages: “skip the queue”, “pick your time”, “see menus in your language”.

> Channels are carried over from Iteration 2, but messages now highlight **Pick Time vs Wait Time**, **multi-language**, and **pickup code** (H9–H12).

---

## 4. Customer Relationships

**CR1 – Self-service clarity**  
UI designed so that students can, without instructions:  
- Notice and use the **language selector** on their own. → H10  
- Understand the difference between **Pick Time** and **Wait Time**. → H11  
- Collect orders using only a notification and code. → H12  
- **Status:** Under validation in i3

**CR2 – Proactive communication**  
- “Expected Wait” shown before placing the order.  
- “Ready” alerts with a clear call-to-action  
  (“Go to Stall X and show this code”).

**CR3 – Light personalisation (future)**  
- Remember last used language and common pickup windows.

---

## 5. Revenue Streams

*(No major change from Iteration 2; still to be validated with merchants.)*  

- Per-order commission from campus restaurants.  
- Subscription / SaaS-style analytics and promotion tools.  
- Paid placements (featured stalls, time-slot badges, banners).

---

## 6. Key Resources

**KR1 – Scheduling & time-choice logic**  
Logic for Pick Time vs Wait Time and ETA calculations.  
- Linked tests: H5, H11

**KR2 – Notification & pickup code system**  
Infrastructure for sending ready alerts and generating unique pickup codes.  
- Linked tests: H6, H12

**KR3 – Multi-language & menu metadata**  
Language selector, translated labels, allergen/spice/dietary tags.  
- Linked tests: H7, H9, H10

**KR4 – UX patterns for self-service**  
Clear, discoverable controls for language, time selection, and tracking orders.  
- Linked tests: H10, H11

---

## 7. Key Activities

- Implement and test the **Pick Time vs Wait Time** flow. → H11  
- Implement and test **language selector + translated UI**. → H9/H10  
- Implement and test **pickup notifications + codes**. → H12  
- Track completion rates, time, and errors for these flows, and link results back to the test cards.

---

## 8. Key Partners

- Campus restaurants (menus, allergen tags, real prep times).  
- University units for branding and on-campus placement (QRs, posters).  
- Language/dietary advisors (accurate translations and allergen info).  

---

## 9. Cost Structure

- Product & engineering (web app, scheduling, notifications, i18n).  
- Content maintenance (menus, translations, dietary/allergen tags).  
- Cloud / infrastructure and basic analytics.  
- On-campus promotion (QR stickers, posters, simple campaigns).

---

## 10. Front Stage vs Back Stage — Iteration 3

**Front Stage (validated / under validation with Iteration 3 tests):**  
- CS1, CS2  
- VP1–VP4  
- Channels focused on QR + web app  
- Customer Relationships (self-service clarity, proactive alerts)  
- Key Activities tied to H9–H12

**Back Stage (future focus):**  
- Merchant-side value propositions and revenue validation  
- Deep analytics, partner integrations, full merchant tools

---

## 11. Mapping to Test Cards

- Iteration 2: **H5 / H6 / H7 / H8**  
  - Queue relief, ready alerts, basic search/i18n, simple navigation.  
- Iteration 3: **H9 / H10 / H11 / H12**  
  - H9 – Multi-language UI improves confidence for non-English users.  
  - H10 – Users can discover and use the language selector unprompted.  
  - H11 – Students can understand and choose between Pick Time and Wait Time.  
  - H12 – Notification + pickup code are enough for self-service pickup.
