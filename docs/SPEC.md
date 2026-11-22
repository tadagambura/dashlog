# DashLog: Spec

**Never miss an MOT, tax or insurance renewal** · #28 of 33 · Wave 3: Seasonal and episodic · Used: A few times a year · Easy · Revenue potential: Low–medium · Plans, Trips & Occasions · Source: New (Claude)

## One-liner

Add your car and DashLog keeps track of MOT, road tax, insurance, servicing and breakdown cover, with reminders well before each date and a simple running-costs log.

## Problem / audience

- **Who it's for:** UK car owners, especially young drivers and households with more than one car.
- **The problem it solves:** MOT, tax and insurance dates are easy to forget and expensive to miss.
- **Example:** A driver gets a reminder 30 days before their insurance renews, compares quotes, and saves money instead of auto-renewing.

## MVP features (ship with only these)

1. Car profile with MOT, tax, insurance, service and breakdown dates
2. Reminders 30, 7 and 1 days before
3. Running-costs log (fuel, repairs)
4. Cost-per-mile view
5. Multiple cars (premium)

## Not in MVP

- MOT history lookup by number plate (official DVSA API, to verify)
- Renewal comparison links
- Document storage

## Monetisation

| Model | Detail |
|---|---|
| Free | One car, with ads |
| Premium | £1.49/month or £9.99 lifetime: multiple cars, cost reports, documents |
| Affiliate | Insurance and breakdown comparisons, clearly labelled |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Renewal reminders |
| Tiny win | Mark done or log a cost |
| Progress | All-dates-sorted status |
| Share | Low |
| Next step | After a renewal, set next year's date |
| Cadence | Several times a year |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone

**Calm.** Smooth, reassuring motion only: gentle ticks, numbers easing into place. No characters, jokes or drama.

- A calm check mark when a renewal is done


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app.
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Car admin; Saving on insurance; Driving costs
- **Shareable output:** Low

## Risks

Long gaps between dates. UK only. Any number-plate lookup must use an official API.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
