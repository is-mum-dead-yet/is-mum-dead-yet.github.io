# Is Mum Dead Yet?

**A slightly inappropriate name for a genuinely caring idea.**

An illustrated, tongue-in-cheek project website about using simple smart-home signals to understand a loved one's everyday activity without turning their home into a surveillance system.

> The question nobody wants to ask. The technology that might help you worry a little less.

## What this is

A public-facing storytelling and inspiration project built around [HomePulse](https://github.com/digitalunity/homepulse), an experimental DIY home-awareness system.

The website explains the idea in everyday language. HomePulse remains the engineering source of truth for hardware choices, code, integration limitations, calibration and validation.

**It is not a commercially available product, a medical monitor, a life detector, or an emergency-response system.** Missing activity should prompt a human check, not an automated conclusion. Detected activity does not prove anyone is safe or well.

## Website

This repository contains a static site designed for GitHub Pages with no application server, cookies, tracking scripts, or third-party asset requests.

The site is published via GitHub Pages from `main` at [is-mum-dead-yet.github.io](https://is-mum-dead-yet.github.io/). No custom domain is needed.

The [real-life questions](https://is-mum-dead-yet.github.io/questions.html) page explains the doorbell, visitor, trolley, lamp-button, phone-battery and privacy scenarios behind the project, including limitations and experimental status.

The [development diary](https://is-mum-dead-yet.github.io/diary.html) tells the story of the experiment in approachable, stage-by-stage chapters. The first published chapter, [Prelude: It started with a lamp](https://is-mum-dead-yet.github.io/diary-prelude.html), describes the everyday Tapo button experience. The published [Day 1: The Bluetooth beacon](https://is-mum-dead-yet.github.io/diary-day-1.html) chapter describes the 19 November 2026 bench setup and initial five-receiver RSSI ingestion, with its limitations. The published [Day 2: Connecting the house](https://is-mum-dead-yet.github.io/diary-day-2.html) chapter describes the 20 November home Tapo bench and cross-source event timeline, with clear distinctions between proven ingestion, unverified capabilities and Mum's later installation. The published [Day 3: Giving the Pi a way home](https://is-mum-dead-yet.github.io/diary-day-3.html) chapter covers the verified restricted AWS SSM remote maintenance setup and read-only USB receiver inspection on 23 November 2026. The first local, read-only monitoring UI was implemented on the Raspberry Pi home bench under [HomePulse PR #29](https://github.com/digitalunity/homepulse/pull/29), and Chris confirmed an Android check. [Day 4: Finally, something I can see](https://is-mum-dead-yet.github.io/diary-day-4.html) tells that story. At the time of this diary update PR #29 remains open, while private browser access (#28), write-capable configuration (#14/#15) and Mum-site commissioning remain future work. Keep private care details, addresses, household event logs and device credentials out of the public diary.

## Direction

- Warm, irreverent artwork and genuinely useful explanatory content.
- A story about *why* this was built, not a sales funnel.
- Activity evidence: trolley movement, deliberate lamp-control presses, door and visitor signals.
- Honest limitations and clear experimental status.
- DIY inspiration, with technical implementation documented separately in HomePulse.

See `docs/` for the working ideas, story outline, and publication checklist.

## Contributing

This is an early creative experiment. Ideas and corrections are welcome via GitHub issues. Do not post personal information, live household activity data, addresses, or home security details.

## Licence

Content and artwork are currently copyright their respective creators. No licence for reuse has been selected yet. The linked HomePulse repository owns its own code and documentation.
