<h1 align="center">Bentilzone Labs</h1>

<p align="center">
  <strong>We build multi-tenant software for operations that run on a floor, a counter, or a loading bay.</strong>
</p>

<p align="center">
  <a href="https://mediusdesk.com">MediusDesk</a> ·
  <a href="mailto:support@mediusdesk.com">Contact</a> ·
  <a href="https://github.com/qbentil">Owner</a>
</p>

---

## What we build

Software for businesses whose work is physical and whose margins live in the details — the queue
at the door, the stock on the shelf, the money at close of day. Every product we ship is
multi-tenant from the first commit, because a business that grows into a second location should
not need a second system.

## Products

### MediusDesk — beauty &amp; personal-care operations

The multi-tenant desk for walk-ins, booked guests, reception and salon operations. Live queues,
guest kiosk check-in, reception checkout with split tenders and tips, retail point of sale,
appointments, staff tabs, inventory and a close of day that balances. Dedicated tenant hostnames
on Premium.

| | |
|---|---|
| **Industry** | Beauty, grooming and personal-care services |
| **Website** | [mediusdesk.com](https://mediusdesk.com) |
| **Sign in** | [app.mediusdesk.com](https://app.mediusdesk.com) |
| **Online bookings** | [bookings.mediusdesk.com](https://bookings.mediusdesk.com) |
| **Support** | [support@mediusdesk.com](mailto:support@mediusdesk.com) |

### Neuros — B2B distribution &amp; wholesale trade

A multi-distributor marketplace where distributors publish a catalogue, buyers raise quotations
and orders against it, stock is reserved before it is promised, and money settles against a
double-entry ledger. Optional escrow holds funds until delivery is confirmed.

| | |
|---|---|
| **Industry** | Wholesale distribution, B2B trade and supply |
| **Status** | **In development** — not yet publicly available |

## How we work

- **Multi-tenant from the first commit.** Separation between organisations is enforced in the data
  layer, not by remembering to add a filter in every query.
- **Decisions are written down.** Each repository carries an ADR log, so the reasoning behind a
  load-bearing choice outlives the person who made it.
- **Built on AWS.** S3 and CloudFront for the front ends, Elastic Beanstalk for the APIs,
  infrastructure described in Terraform rather than clicked together.
- **An autonomous teammate.** BentilzoneDevAgent picks up tracked work, opens pull requests and
  publishes the evidence behind every change. A human reviews and merges — always.

## Contact

General and support: **[support@mediusdesk.com](mailto:support@mediusdesk.com)**

Most repositories here are private. If you are looking for something specific, write to us.

---

<p align="center">
  Bentilzone Labs is owned and operated by
  <a href="https://github.com/qbentil"><strong>Bentil Shadrack</strong></a>.
</p>
