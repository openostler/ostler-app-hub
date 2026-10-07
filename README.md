# Ostler Community client

The open in-car client for the Ostler Community service.

Part of [Ostler](https://github.com/openostler/ostler), an open, local-first,
smart-home-like ecosystem for your car. Ostler is built like a phone OS: the
platform repo is the bare system, and every feature is an app or pack in its
own repo, installed from the Store.

Status: empty. This project follows UX first: design, then UI against
recorded fixtures, then wiring. Nothing is built here until the app's design
brief is approved. The briefs live in
`openostler/ostler/references/design/2026-10/brief/`.

Licence: AGPL-3.0-or-later. Contributions are
accepted under the project CLA.

## What this repo holds

- **Owner in the brief:** `app:community`.
- **Contents:** the open in-car client of the closed Ostler-run hub: Discover, Forum, Help (end-to-end encrypted help threads), Mine, and wiki links; phase H1 of its spec.
- **Design brief:** [60-apps-hub-a](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/60-apps-hub-a.md), [60-apps-hub-b](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/60-apps-hub-b.md), [60-apps-hub-c](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/60-apps-hub-c.md), [60-apps-hub-d](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/60-apps-hub-d.md) (index: [99-index](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/99-index-a.md)).
- **Spec:** [community-hub](https://github.com/openostler/ostler/blob/main/specs/2026-10-07-community-hub-design.md).
- **Code that moves here later** ([ADR-0046](https://github.com/openostler/ostler/blob/main/decisions/adr-0046-empty-os-every-app-an-add-on.md)): the empty `community/` package. It moves only after this app's designs are approved ([ADR-0045](https://github.com/openostler/ostler/blob/main/decisions/adr-0045-ux-first.md)).
