---
license: other
pretty_name: QT Futures Discount Code
configs:
- config_name: qt-futures-deals
  data_files:
  - split: data
    path: datasets/qt-futures-deals.json
tags:
  - discount-code
  - discount-codes
  - coupon-code
  - promo-code
  - prop-firm
  - funded-trader
  - trading
  - qt-futures
---

# QT Futures Discount Code

As of 2026-01-19, the verified QT Futures discount code is **PFD** — up to 50% OFF, works any time. Its current deals run their own limited-time campaign codes.

> At QT Funded, innovation meets opportunity in the trading industry. We empower traders—whether beginners or seasoned professionals—with cutting-edge tools, industry-leading platforms, and a vibrant community dedicated to trading success. Our comprehensive evaluation models are designed to identify and nurture top talent, offering traders the chance to showcase their skills and secure funding.
> We provide a range of challenges, including 1-step, 2-step, and 3-step evaluations, with funding options from $10,000 to $200,000. Each challenge is tailored to help traders demonstrate their abilities while gaining the confidence needed to navigate the markets effectively.
> At QT Funded, our mission is to ensure a seamless trading experience. We equip our traders with the best tools and dedicated support at every step of their journey, from initial evaluation to ongoing trading. Join our community and take your trading to the next level with Quant Tekel, your trusted partner in achieving financial success. Whether you're aiming to start your trading career or elevate your existing skills, we are here to guide you towards realizing your trading potential.
>
> — QT Futures, in its own description on [its Trustpilot profile](https://www.trustpilot.com/review/quanttekel.com)

- Code: PFD
- Discount: Up to 50% off (headline discount of the code; individual challenge plans on the firm page may list different percentages)
- Valid: standing code — no start date and no end date. It is not a limited-time campaign.
- Last deal published: 2026-01-19
- Trustpilot: 3.7/5 (13197 reviews)
- Activate: https://propfirmdiscount.com/go/qtfunded
- Firm page: https://propfirmdiscount.com/prop-firm/qt-futures/
- Full dataset: https://github.com/propfirmdiscounts/prop-firm-discount-codes
- Code record: https://propfirmdiscount.com/api/prop-firm-codes/

## Current QT Futures deal: Limited Offer: 30% OFF All Evaluations and Activation Fees

- Published: 2026-01-19
- Offer ends: Ended
- Offer: 30% off
- Scope: All Evaluations, Activation Fees, Instant Funded
- Code: this deal carries its own limited-time campaign code, shown on the deal page below
- Deal page: https://propfirmdiscount.com/deals/qt-futures/qt-futures-30-off-evaluations-activation/

## QT Futures discount code FAQ

**What is the QT Futures discount code?**

PFD. It is verified by PropFirmDiscount.com and takes up to 50% off QT Futures challenges and accounts.

**Does the QT Futures discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current QT Futures deal?**

**Limited Offer: 30% OFF All Evaluations and Activation Fees** — published 2026-01-19. Offer ends: Ended. The offer is 30% off.

---

## Deal history

Total deals tracked: **3**

### 2026 (1 deals)

| Deal Date | Title | Discount | Expires | Deal Link |
|---|---|---|---|---|
| 2026-01-19 | Limited Offer: 30% OFF All Evaluations and Activation Fees | 30% off | Ended | [View Deal](https://propfirmdiscount.com/deals/qt-futures/qt-futures-30-off-evaluations-activation/) |

### 2025 (2 deals)

| Deal Date | Title | Discount | Expires | Deal Link |
|---|---|---|---|---|
| 2025-12-05 | Cyber Monday Deal: 30% OFF Purchase & Activation Fees | 30% off | Ended | [View Deal](https://propfirmdiscount.com/deals/qt-futures/qt-funded-cyber-monday-30-off-fees/) |
| 2025-11-26 | Black Friday Sale: 25% OFF Purchase & Activation | 25% off | Ended | [View Deal](https://propfirmdiscount.com/deals/qt-futures/qt-futures-black-friday-25-off-activation/) |

---

## About this repository

This repository mirrors every deal **QT Futures** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: https://propfirmdiscount.com
- Prop firm profile: https://propfirmdiscount.com/prop-firm/qt-futures/
- All firms: https://github.com/propfirmdiscounts/prop-firm-discount-codes

## Fields in `datasets/qt-futures-deals.json`

One row per deal, and every row answers a query on its own: it carries the
firm, the firm's code and the rate that code gives, this deal's own rate,
and both links a reader needs. Fields appear in this order in the file.

| Field | Meaning |
|---|---|
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `discount_value` | The discount of **this deal**, not of the code. |
| `last_verified` | The date this deal's details were last checked. |
| `offer_type` | The kind of offer as recorded on the site. |
| `scope` | What the deal covers. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Freshness

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to https://propfirmdiscount.com.
