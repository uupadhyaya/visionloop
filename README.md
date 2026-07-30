# Visionloop
# VisionLoop

A six-step circular narrative framework for storytellers, sold across three tiers: a self-guided worksheet, an AI-guided builder, and a done-for-you engagement.

VisionLoop opens with sight and closes with a vision that redeems and expands that sight, with a paradox as the hinge in the middle. Full framework explanation lives in `VisionLoop-Public-Article.md`.

## Live pricing

| Tier | Price | What it is |
|---|---|---|
| Self-Guided Worksheet | $49 | Downloadable PDF, sold on Gumroad |
| AI-Guided Build | $199 | Interactive tool, access sent after payment |
| Done-For-You | $1,500 | 1:1 engagement, delivered personally |

## Files in this project

### Public-facing
- **`visionloop.html`** — the landing page. Framework overview (titles only, no explanations), two proof examples ("Built for a Raise"), the three pricing tiles, and a contact section that routes every buy button to an email/form instead of direct checkout.
- **`visionloop-working-model.html`** — interactive diagram. Click through the six steps; toggle between the plain framework and three applied examples (YTL, Telvox, SnapLink).
- **`VisionLoop-Public-Article.md`** — the publishable article for LinkedIn, Medium, or Substack. Explains the framework in depth but deliberately withholds the worksheet's prompts, prompt bank, and full worked examples.
- **`VisionLoop-Offer-Suite.pdf`** — six-page external one-pager, one page per tier plus a framework overview, for sending to prospects directly.
- **`VisionLoop-Worksheet.pdf`** — the actual $49 product. Six-step worksheet, paradox-line prompt bank, one worked example (StarScout).
- **`visionloop-cover-600x600.jpg`**, **`visionloop-product-cover-1280x720.jpg`**, **`visionloop-avatar-400x400.png`** — Gumroad thumbnail, product-page cover, and profile avatar.

### Internal only — never publish these
- **`VisionLoop-Practitioner-Guide.docx`** — how to run discovery calls, drafting rules per step, the pre-send quality checklist, and the delivery-call structure for Done-For-You engagements.
- **`VisionLoop-Sales-Playbook.docx`** — positioning, per-tier sales scripts, objection answers, pricing posture, and the upward handoff between tiers.

### Not yet built / referenced but pending
- **`visionloop-builder.html`** — the AI-Guided Build tool. Built and functional, but currently has no payment gate; access is sent manually after a buyer pays.

## What's still needed before this is fully live

1. **Gumroad**: connect a payment method, publish the $49 worksheet, get the live product link.
2. **Contact form**: `visionloop.html`'s form posts through FormSubmit to `namaskar@visionloop.co`. That address must exist (domain email forwarding or a provider like Zoho Mail), and the first-ever submission triggers a one-time FormSubmit activation email that must be clicked before forwarding works.
3. **Hosting**: upload `visionloop.html` and `visionloop-working-model.html` to the same server folder (e.g. the Hetzner box hosting InsightGoals.com) so internal links resolve.
4. **Tier 2 access gate**: decide between trust-based delivery (send the builder link manually after payment) or building a real access-code check into `visionloop-builder.html`.
5. **Domain**: `visionloop.co` is referenced across the materials as the working domain; register it or swap in the real one.

## Brand

Ink (`#12121f`), brass (`#c9a24b`), parchment (`#ede7da`), with a rust/signal accent (`#b5533c`) reserved specifically for the paradox step. Typefaces: Newsreader (serif, display) and Space Grotesk (sans, body/UI).

## The one rule

Never invent facts, numbers, or claims a client didn't give you, in any tier, in any material. See the Practitioner Guide and Sales Playbook for the full reasoning.
