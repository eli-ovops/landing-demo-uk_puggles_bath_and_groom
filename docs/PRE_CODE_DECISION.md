# PRE_CODE_DECISION — Puggles Bath & Groom v2

Date: 2026-09-02. Direction-level rebuild count: 1.

## Rebuild trigger and decision

**FAIL — REDESIGN DIRECTION:** the prior green, quiet-care direction was rejected by the user. It read as a generic pet-service template and weakened the existing Puggles identity: purple utility bar, navy dog outline, coral bubble wordmark and fuller service/review/contact hierarchy. It is retired, not patched.

**PRE-CODE GATE = AWAITING INDEPENDENT REVIEW.** No v2 customer-visible HTML/CSS/JS has been written.

Design Read: a local Reading groomer with an already recognisable, playful graphic identity; the concept should feel like an edited Puggles noticeboard, not a luxury-spa template. Three dials: `SOUL 9 / SPECTACLE 3 / DENSITY 8`. The substrate is warm paper-white, Puggles plum, coral, and deep navy. A static field of oversized bubbles, asymmetric menu tiles and dense utility details carry the brand energy without copying the existing site code. There is no automatic animation.

### Two materially distinct directions

1. **Chosen — Puggles brandboard.** A plum utility strip, oversized official wordmark, graphic bubble field and compact navigation make the existing identity visible immediately. An irregular, illustrated service menu leads through care, review signal and practical visit information. Official imagery is distributed through the full page as atmosphere, never asserted as verified customer work.
2. **Rejected — prior “Care in clear view”.** A dark-green split hero, editorial ledger and sparse proof bands. It had a different palette but, more importantly, a generic spa-like hero system, low information density and a service-site structure that could be reused for another groomer. User rejection confirms it does not satisfy the purchase thesis.

Explicit refusals: no green spa palette, no generic “calmer kind” headline, no numbered `01/02/03` cards, no isolated giant review statistic, no equal-card grid, no fake booking or form, and no empty scenic whitespace.

## Current Offer Purchase Thesis

United Kingdom: `GBP / £99 AS-SHOWN HANDOVER or £199 ONE PERSONALISED UPDATE`.

Within five seconds, a visitor can recognise Puggles, dog grooming in Reading, its service menu, its established review signal and a direct call route. The commercial increment is an identity-led, full static service and contact narrative that carries the existing brand beyond a sparse or broken first impression; it does not claim to operate bookings. £199 remains one consolidated customer-supplied text/image revision plus QA.

## Research-to-Demo Activation Matrix

| ID | Customer fact / asset | Source class | Unique disposition | Exact v2 page mapping | Constraint |
| --- | --- | --- | --- | ---| --- |
| R01 | Puggles logo | Official owned site | DIRECT USE | `.brand-logo`, `.brand-lockup`, footer | Concept only; not transfer-cleared |
| R02 | Dog-bath image A-002 | Official owned site | DIRECT USE | `.feature-bath` service menu | Atmosphere only; not real-work proof |
| R03 | Towel-dog image A-003 | Official owned site | DIRECT USE | `.care-visual` | Filename labels AI generation; no real-dog claim |
| R04 | Bathtub-dog image A-004 | Official owned site | DIRECT USE | `.call-image` closing panel | Atmosphere only; not real-work proof |
| R05 | Reading professional grooming | Official site | FACT/PARAPHRASE USE | Hero and footer | No unverified catchment claim |
| R06 | Bath & Go; Bath & Trim; Bath, Groom & Pamper; wider care list incl. hand stripping | Official site | FACT/PARAPHRASE USE | `#services` | No price or availability claim |
| R07 | `381+ Reviews` navigation label | Official site | FACT/PARAPHRASE USE | `.review-chip`, `#reviews` | No quotation, rating or outcome invented |
| R08 | Telephone and public matching-domain email route | Official site / public business listing | LOCATION/VISIT USE | Utility strip, `#visit` and contact details | `tel:` / `mailto:` only; no form/tracking/booking |
| R09 | Beech Hill address | Official contact route | LOCATION/VISIT USE | `#visit` | Exact address only |
| R10 | Clifford, Chief stylist; Level 3 City and Guild Dog Groomer; animal-care/handling and Dog & Cat First Aid claims | Official-site claim | FACT/PARAPHRASE USE | `#care` | Attribute as Puggles' stated background; no badge or independently verified credential claim |
| R11 | Before & After gallery route | Official owned site | LOCATION/VISIT USE | `#services .gallery-link` | Link to official route only; do not reuse individual transformation images |
| R12 | Board and staff portraits | Official owned site | RETIRED / SPLIT | R22–R24 | The former group is no longer excluded; its three members are individually activated below |
| R13 | Prices, availability, hours, booking destination | Dynamic | TIME-SENSITIVE VERIFY/REPHRASE | `#visit`, utility strip: no price, availability or booking claim; stable phone route only | No dynamic claim is carried into the concept |

Original-matrix coverage at v2 was 13 items; it is superseded by the current reconciled coverage statement below. R12 has no remaining unique fact or asset and is not counted independently.

## Full-page visual storyboard

| Section | Activation / commercial task | Asset or fact / desktop crop | 390px behaviour | Motion / rights |
| --- | --- | --- | --- | --- |
| Utility + brand field | R01,R05,R07,R08: recognise brand, Reading and proof before scrolling | A-001 logo unchanged; Reading, `381+ Reviews`, phone | Utility wrap becomes two short rows; logo retains full mark above copy; bubble field crops safely to the right | No motion; logo is official-public concept-only asset |
| Service menu | R02,R06,R11: make named choices tangible and preserve the official Before & Afters route | A-002, 58% centre crop; Bath & Go / Bath & Trim / Bath, Groom & Pamper; official gallery route | Image tile becomes full-width first, 54% centre crop; text tiles then hand-stripping and official-gallery link | No motion; A-002 is official-public atmosphere, not real-work proof; gallery has no copied work image |
| Care notice | R03,R10: place care promise and stated stylist background in a Puggles context | A-003, 62% centre crop; carefully attributed Clifford facts | Image precedes the coral note, 55% centre crop | No motion; A-003 is official-public, AI-labelled source, not a real-dog claim |
| Review signal | R07: establish a public factual trust cue | Official `381+ Reviews` text marker | Compact two-line plum/coral ribbon, no statistic monument | No motion; official fact only, no review quote/rating |
| Call + visit | R04,R08,R09,R13: practical next action without fake workflow | A-004, 52% centre crop; phone, public business email and exact address; time-sensitive facts deliberately absent | Image and contact panel stack, 50% centre crop; phone and email remain the only actions | No motion; A-004 is official-public atmosphere, concept-only; R13 is a stable rephrased contact route |

## Reference board

1. https://www.groomsofglasgow.co.uk/ — opened 2026-09-02; local strong peer reference for concise service grouping only, not copy/code/assets/layout.
2. https://www.hamptonhounds.co.uk/ — opened 2026-09-02; mature local-service reference for a direct call conversion path only, not copy/code/assets/layout.
3. https://www.doggroomingglasgow.com/ — opened 2026-09-02; care/composition reference for putting reassurance before contact only, not copy/code/assets/layout.

## Implementation map and Skill receipt

| Final task | Activation | Selector / file | Desktop and mobile responsibility | Prohibited fallback |
| --- | --- | --- | --- | --- |
| Brand recognition | R01,R05,R07,R08 | `index.html .masthead`, `v2.css` | Dense brandboard; no dead hero space; vertically sequenced mobile | generic centred text hero |
| Service understanding | R02,R06,R11 | `#services`, `.service-menu` | Asymmetric menu, factual service list and official gallery route; stacked sequence mobile | equal cards / invented packages |
| Care reassurance | R03,R10 | `#care`, `.care-note` | Image and carefully attributed stylist background | credentials badges / independent credential claim |
| Trust cue | R07 | `#reviews` | Integrated ribbon | fake stars/reviews |
| Direct action | R04,R08,R09,R13 | `#visit` | phone + public business email + exact address, no account flow | availability, booking or form |

- `website-delivery-sop`: L0 local-static concept boundary applied; no `site.yaml`, hosting, deployment or public link action. DS-002B v2.5 SHA-256 `5b70133e7a155a713c130d07d883afffbd1f57eaa7bfc7c2e2c3dfc9f9bb926a`.
- `finesse-ui`: the redesign audit changed the design read from calm generic grooming to Puggles brandboard; it directly selected SOUL/DENSITY, brand-derived tokens, oversized wordmark, asymmetric menu and anti-cheap scan.
- `design-taste-frontend`: directly rejected equal cards, a centred generic hero and predictable section rhythm; it selected dense utility information, varied image/copy proportions and an intentional mobile order.
- `media-use`: asset inventory, sources, hashes and transfer disposition govern all three official images and logo. No install, login, upload or treatment was used.

## Cross-demo and self-review

Compared with `client_uk_shelleys_poochie_parlour/demo_20260901/PRE_CODE_DECISION.md`, `client_uk_fluffandtuff_dog_groomers/demo_20260901/INDEPENDENT_PRE_CODE_REVIEW.md`, and the retired Puggles green version: the hero engine, palette, typography role, information density, image distribution, service treatment, proof treatment, CTA and bottom-40 composition are deliberately distinct. No material template pattern is retained.

The first screen must identify Puggles before explanatory copy. Every visible claim traces to the intelligence file. Static `tel:`, `mailto:` and the official Before & Afters route are the only actions; there are no forms, booking, analytics, storage, payment, external fonts or embeds. This is a content activation, not a new design direction; prior independent pre-code approval remains applicable, with the above boundaries added before implementation.

## 2026-09-03 content-depth addendum

Fresh official-page recheck found additional material that the initial concept had not activated. This is a content-depth correction, not a new visual direction.

| ID | Officially published material | Visible activation | Boundary |
| --- | --- | --- | --- |
| R14 | Full-groom process: customised shampoo/conditioner, hand dry and brush, health check, ear cleanse, eye-stain removal, feet/nail trim, clipping/scissoring tailored to breed and family lifestyle | `#full-groom` | Describe as the published full-groom process; no availability or outcome guarantee |
| R15 | Official service-area list: Reading, Spencers Wood, Three Miles Cross, Swallowfield, Riseley, Earley, Lower Earley, Mortimer, Burghfield & Burghfield Common, Tilehurst, Calcot, Southcote | `#areas` | Explicitly say “areas listed by Puggles”; not an expanded catchment claim |
| R16 | Official review page states `381+ satisfied client reviews`; its currently published entries repeatedly discuss care for nervous/older dogs, consultation, communication and repeat visits | `#reviews` | Summarise themes only; no fabricated star rating, review count beyond official marker, quote, reviewer name or claimed result |
| R17 | Official News lists: “Why Do I Need to Brush My Dog?” (29/10/2025), “20 ways coconut oil can help your pets” (28/10/2024), “Why grooming is important?” (28/10/2024) | `#notes` | Link titles to official News; dates labelled as published pages, no medical advice added |

R13 remains unchanged: do not surface dynamic prices, availability, opening hours or booking destination. The addendum retains the static-only boundary and requires the same desktop/390px and client-visible-text QA after implementation.

## 2026-09-03 user-directed current-price activation

The user explicitly requested that all known, suitable customer content be included. A fresh official services-page check on 2026-09-03 verified the current published `PRICE FROM` tables and charge conditions. This supersedes R13 only for prices and their dated disclosure; it does **not** authorise availability, opening hours, booking, payment or a form.

| ID | Officially published material | Visible activation | Boundary |
| --- | --- | --- | --- |
| R18 | Bath & Go: £25 / £30 / £35 / £45 / £POA; Bath & Trim: £35 / £40 / £45 / £50 / £POA; Bath, Groom & Pamper: £45 / £49 / £54 / £59 / £POA (Toy / Small / Medium / Large / Extra Large) | `#price-guide` | State `Published price guide checked 03 Sep 2026 — confirm your dog’s quote directly with Puggles`; no availability/payment/booking claim |
| R19 | Official service page says badly matted fur can incur additional costs and fleas found in fur incur an extra £10 | `#price-guide` | Present as a discreet official-page note, not a universal quote or penalty invented by the demo |
| R20 | Official website schema identifies Facebook `facebook.com/pugglesdoggrooming`; footer links Privacy, Cookie Policy (UK) and Terms & Conditions (Grooming) | footer utility links | Official route links only; no unresearched social-feed content or legal interpretation |

## 2026-09-03 visual and motion refinement

The three existing official-public source images were inspected at native dimensions (A-002 `2560×1656`, A-003 `2560×1707`, A-004 `2560×839`). They remain sufficiently sharp for their current responsive crops. No image-generation repair is used: it would add unsupported pixels to customer-owned visual material and reduce its factual status. CSS crop positioning and overlays provide the required layout control without altering source imagery.

**Superseded by the fidelity rebuild below:** the former bubble-drift motion receipt belongs only to retired v2 and is not implemented in the current direction.

## 2026-09-03 customer-page fidelity rebuild

**FAIL — REDESIGN DIRECTION:** the v2 white graphic-bubble hero is rejected by the user after comparison with Puggles’ current public homepage. It makes the customer’s own strongest first-screen material — the multi-dog image, direct Reading promise and clear call route — less immediate. This is a direction-level rebuild, not a cosmetic patch. **Direction-level rebuild count: 2. PRE-CODE GATE = AWAITING INDEPENDENT REVIEW.**

### Chosen direction and alternative

1. **Chosen — “Dogs first, details close.”** A compact white brand/navigation rail sits above an edge-to-edge official multi-dog hero. A deep navy photographic veil gives the official message `Professional dog grooming in Reading` enough authority without hiding the image. The middle keeps the service/price/care story; the lower page becomes a warm Puggles board and a tangible `Find us` route with address, locality and a Google Maps *external link*.
2. **Rejected — “Portrait collage”.** A patchwork of services, board portraits and a map-like graphic in the first screen. It would add facts, but weaken the immediate dog-first recognition that the customer’s original hero already proves works.

Design Read: `SOUL 9 / SPECTACLE 3 / DENSITY 8`. The existing Puggles purple, navy, coral and warm paper remain, but the substrate changes from abstract graphic-first to official-dog-image-first. The anti-cheap rule is that no decorative bubble, generic slogan or oversized blank field may compete with the customer’s own decisive visual evidence.

### Added research-to-demo activation

| ID | Customer fact / asset | Source class | Exact visible mapping | Boundary |
| --- | --- | --- | --- | --- |
| R21 | Officially published **AI-generated** multi-dog homepage hero A-005 and `Professional dog grooming in Reading` | Official owned site | `.photo-hero` | AI-generated official atmosphere only; not represented as client dogs, real work or an actual Puggles group |
| R22 | Frankie, `Chief Tickle Officer`, and officially published board story | Official owned site | `#board .board-card--frankie` | Concise paraphrase only; A-006 used at small native-appropriate thumbnail scale |
| R23 | Aggie, `Chief Strategic Officer`, and officially published board story | Official owned site | `#board .board-card--aggie` | Concise paraphrase only; A-007 used at small native-appropriate thumbnail scale |
| R24 | Clifford, `Chief stylist`, and officially published background | Official owned site | `#board .board-card--clifford` | Carefully attributed, concise paraphrase; A-008 used at small thumbnail scale |
| R25 | `3 Mays Hill Cottages, Beech Hill, Reading, Berkshire, RG7 1JA` and official service-area list | Official contact/services pages | `#find-us` | Native location module plus an outbound Google Maps query link; no embedded third-party map, cookies, tracking, form, or claim of availability |
| R26 | Pug and Max memorial portraits/stories published on the official homepage | Official owned site | Explicit exclusion | None | Sensitive historic memorial content; not used in the current-service decision journey |

**Current reconciled coverage:** `25` independently disposed items: direct official-asset use `8` (R01–R04, R21–R24); fact/paraphrase `10` (R05–R07, R10, R14–R19); location/visit/link `5` (R08, R09, R11, R20, R25); time-sensitive rephrase `1` (R13); explicit exclusion `1` (R26). R12 is a retired grouping, not an additional item: its active Frankie/Aggie/Clifford material is fully split across R22–R24, while the separate Pug/Max memorial material is explicitly excluded at R26. Every counted item has exactly one disposition. External booking/forms/availability and unverified social content remain outside the suitable verified set and are deliberately absent.

### Revised full-page storyboard and implementation map

| Section | Customer task / activation | Desktop and 390px treatment | Motion / static fallback |
| --- | --- | --- | --- |
| White rail + photo hero | R01,R05,R07,R08,R21: recognise Puggles, dog grooming, Reading and direct call instantly | Full-bleed A-005, an officially published AI-generated atmosphere image, with dark veil, concise official promise and two anchored actions; 390px retains dog faces, single-column copy and visible call | No ambient graphic movement; one 360ms copy entrance only, then fully static; reduced-motion is static from first paint |
| Service through reviews | R02–R20: preserve complete service, price, care, review, areas and news content | Existing varied sections remain, with no text-only tail | Existing hover-only media feedback; no automatic secondary layer |
| Puggles board | R22–R24: restore warmth/personality the official site provides | Three asymmetric compact cards with official thumbnails at 92px; mobile stacks without scaling images past source-appropriate size | Static portraits; no generated or enhanced pixels |
| Find us | R08,R09,R15,R25: make the address and route as visible as phone | Native address/pin/directions panel; Google Maps opens only after visitor action; mobile keeps the address and map button together | Static location graphic; no iframe/cookie or location tracking |

New implementation selectors: `hero-refresh.css` owns `.masthead`, `.photo-hero`, `.puggles-board`, `.find-us`, and `.map-route`; it is loaded last so it cleanly replaces the retired bubble hero. `motion-fix.css` is updated to remove bubble movement. The map route is the exact Google Maps destination query for the published address; it opens in a new tab only after a user click, with no iframe, preloading or map data collection. This is a content-and-visual rebuild; its independent pre-code and final desktop/390px review are required before it can be client-showable.

Current motion receipt: one 360ms hero-copy rise/fade establishes reading order; all other visual layers are static. Link/button feedback and image-card hover use short interaction-only transitions. `prefers-reduced-motion: reduce` removes every non-essential transition and animation. This supersedes the retired bubble-drift receipt above and has no third-party runtime, tracking or pixel alteration.

## 2026-09-03 replacement-ready 9/10 refinement

**REPLACEMENT-READY PRE-CODE = AWAITING INDEPENDENT REVIEW.** This is a whole-page refinement of the current accepted direction, not a new brand/asset direction. It fixes the documented shortfall: the Hero must beat rather than merely resemble the current customer page; services must become an at-a-glance decision route; proof, board, place and call must read as one conversion sequence; and both viewports must be fully audited.

### Current-site baseline and one-to-one disposition

| Baseline | Current official source/value | Disposition / final target |
| --- | --- | --- |
| B01 | Homepage: logo, multi-dog image, `Professional Dog Grooming in Reading`, call action | CARRY: `.photo-hero`, hero rail and `tel:` CTA; sharpen 390px crop and headline wrapping |
| B02 | Services: Bath & Go / Bath & Trim / Bath, Groom & Pamper and price tables | CARRY: `#services`, `#price-guide`; each service gets a published-scope / includes / from-price cue |
| B03 | Reviews: 381+ marker and care/communication themes | CONSOLIDATE: `#reviews` becomes a compact proof strip directly after the selection/price route |
| B04 | Board: Frankie, Aggie, Clifford profiles and official portraits | CARRY: `#board`, reduced to a human proof bridge, after service trust rather than an isolated story island |
| B05 | Contact: phone, email, exact address, map and service-area list | CONSOLIDATE: `#find-us` + `#visit`; exact Google Maps external link, `tel:` and `mailto:` remain real actions; original form is excluded because a static demo cannot safely submit it and phone/email are working replacements |
| B06 | Facebook, Before & Afters, News, grooming terms/privacy/cookie routes | EXTERNAL-LINK: official outbound routes remain in services, news and footer |
| B07 | Pug/Max memorial content | EXCLUDE: sensitive historic memorial content, not part of a current-service decision journey |

Baseline disposition: 7/7. No logo, location, map, contact, main service or official social/action path is silently lost.

### Exact 9/10 implementation changes

1. **Hero:** mobile headline uses deliberate two-line wrapping, no overflow; crop holds the central dog face and CTA clear zone. The low-priority concept notice leaves the immediate decision area.
2. **Service decision:** each of the three named official services obtains a non-invented starting cue from the published scope and its `from` price; image/story rhythm is diversified so cards do not become a text-only run.
3. **Proof chain:** price, care credentials and review themes become a contiguous sequence, then lead into the board as personality proof rather than a detached card collection.
4. **Bottom 40%:** `Find us` owns navigation/address/areas; `Visit` owns a single call/email next step. Their actions no longer duplicate each other.
5. **QA:** final local inspection at 1440x900 and 390x844 must prove no horizontal overflow, all mapped image subjects visible, visible complete navigation, real hrefs, no internal text and reduced-motion static fallback.

### Service decision mapping (official scope, non-recommendatory)

| Service | Exact visible cue | Official basis | Final selector / viewport behaviour |
| --- | --- | --- | --- |
| Bath & Go | `Freshen up · from £25` and `Warm cleansing shower, one customised shampoo, conditioner, hand dry & brush.` | Official Bath & Go description and Toy `PRICE FROM` | `.service-card--go`; desktop compact fact line beneath title, 390px follows title before image detail |
| Bath & Trim | `Keep it tidy · from £35` and `Two shampoos, conditioner, hand dry & brush, plus a practical coat trim.` | Official Bath & Trim description and Toy `PRICE FROM` | `.service-card--trim`; same reading order and no claimed suitability/outcome |
| Bath, Groom & Pamper | `Full groom · from £45` and `Consultation, full body health check, ear cleanse, eye-stain removal, feet/nail trim and breed/lifestyle clipping or scissoring.` | Official Bath, Groom & Pamper description and Toy `PRICE FROM` | `.service-card--pamper`; desktop detail is beside image, 390px is below title and above call route |

`From` is explicitly a dated published-price cue, not a quote, availability statement or recommendation. The price guide remains the exact full table and states its checked date.

## 2026-09-03 map-display clarification

The user explicitly requested that the map itself be shown, not merely linked. For this local-only Concept Demo, `#find-us .map-frame` therefore uses a lazy Google Maps iframe for the exact published address. It has `referrerpolicy="no-referrer"`, contains no analytics or our tracking, no form/booking/payment flow, and keeps the visible `target=_blank rel=noopener noreferrer` Google Maps route as a direct alternative. This is a local-preview display choice only; it is not deployment or outreach.
