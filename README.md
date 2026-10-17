# Awesome Self-Hosted Newsletter

> Curated, link-verified tools for running your own newsletter, mailing list and sending stack.

Renting an audience from a newsletter SaaS means renting the list, the deliverability and the price. This list indexes the tooling to own that stack instead: newsletter platforms and list managers, the mail servers and sending APIs underneath them, RSS-to-email automation, email authoring frameworks, and the forms and marketing automation that feed a list. Every link is checked to be live when this README is regenerated.

> [!NOTE]
> Compiled from public sources — no independent testing of the linked projects.

## Contents

- [📧 Newsletter Platforms and List Managers](#newsletter-platforms-and-list-managers)
- [🛰️ Sending Infrastructure and Mail Servers](#sending-infrastructure-and-mail-servers)
- [📝 RSS to Newsletter and Email Authoring](#rss-to-newsletter-and-email-authoring)
- [🪄 Audience, Forms and Subscription Management](#audience-forms-and-subscription-management)
- [🔁 Marketing Automation and CRM-Adjacent](#marketing-automation-and-crm-adjacent)

## 📧 Newsletter Platforms and List Managers

The applications you actually log into: write a campaign, manage subscribers, send it.

| Project | What it is | Tags |
|---|---|---|
| [Ghost](https://github.com/TryGhost/Ghost) | Independent publishing platform with memberships, subscriptions and built-in newsletters. | `publishing`, `memberships`, `node` |
| [listmonk](https://github.com/knadh/listmonk) | High-performance self-hosted newsletter and mailing list manager with a modern dashboard. | `newsletter`, `mailing-list`, `go` |
| [BillionMail](https://github.com/Billionmail/BillionMail) | Open-source mail server, newsletter and email marketing stack, fully self-hosted. | `newsletter`, `mail-server`, `email-marketing` |
| [mailtrain](https://github.com/Mailtrain-org/mailtrain) | Self hosted newsletter app. | `newsletter`, `node`, `self-hosted` |
| [notifuse](https://github.com/Notifuse/notifuse) | Open-source, self-hosted newsletter, email marketing and transactional email platform. | `newsletter`, `mjml`, `transactional` |
| [keila](https://github.com/pentacent/keila) | Open source newsletter tool built in Elixir. | `newsletter`, `elixir`, `self-hosted` |
| [sendportal](https://github.com/mettle/sendportal) | Open-source self-hosted email marketing for managing your own newsletters at lower cost. | `email-marketing`, `laravel`, `lists` |
| [phplist3](https://github.com/phpList/phplist3) | Open source email marketing manager for creating, sending and analysing campaigns. | `email-marketing`, `php`, `lists` |
| [colossus](https://github.com/vitorfs/colossus) | Self-hosted email marketing solution written in Django. | `email-marketing`, `django`, `self-hosted` |
| [Mailcoach](https://github.com/spatie/Mailcoach) | A self-hosted email list manager in a modern jacket. | `email-marketing`, `laravel`, `lists` |

## 🛰️ Sending Infrastructure and Mail Servers

What sits under the newsletter: the MTA, the delivery platform and the transactional API.

| Project | What it is | Tags |
|---|---|---|
| [docker-mailserver](https://github.com/docker-mailserver/docker-mailserver) | Production-ready fullstack mail server (SMTP, IMAP, LDAP, antispam, antivirus) in a container. | `mail-server`, `smtp`, `imap` |
| [postal](https://github.com/postalserver/postal) | A fully featured open source mail delivery platform for incoming and outgoing e-mail. | `mail-server`, `smtp`, `delivery` |
| [stalwart](https://github.com/stalwartlabs/stalwart) | All-in-one mail and collaboration server fluent in IMAP, JMAP, SMTP, CalDAV and CardDAV. | `mail-server`, `jmap`, `smtp` |
| [mailcow-dockerized](https://github.com/mailcow/mailcow-dockerized) | A Docker-based mail server suite bundling the full mail stack. | `mail-server`, `docker`, `smtp` |
| [Mailu](https://github.com/Mailu/Mailu) | Insular email distribution — a mail server shipped as Docker images. | `mail-server`, `docker`, `smtp` |
| [mox](https://github.com/mjl-/mox) | Modern full-featured open source secure mail server for low-maintenance self-hosted email. | `mail-server`, `smtp`, `go` |
| [cuttlefish](https://github.com/mlandauer/cuttlefish) | Transactional email server with a web interface. | `transactional-email`, `smtp`, `web-ui` |
| [relay](https://github.com/hyvor/relay) | Open-source email API for developers, a cloud and self-hosted alternative to SES, Mailgun and SendGrid. | `email-api`, `transactional`, `ses` |

## 📝 RSS to Newsletter and Email Authoring

Turning sources into issues: feed-to-email automation and the markup that makes email render.

| Project | What it is | Tags |
|---|---|---|
| [RSSHub](https://github.com/DIYgod/RSSHub) | Everything is RSSible — generates RSS feeds from many sources that have none. | `rss`, `feeds`, `self-hosted` |
| [MJML](https://github.com/mjmlio/mjml) | A markup framework that makes writing responsive email less painful. | `email`, `markup`, `responsive` |
| [rss2email](https://github.com/rss2email/rss2email) | Forward RSS feeds to your email address, community maintained. | `rss`, `email`, `cli` |
| [rss2newsletter](https://github.com/ElliotKillick/rss2newsletter) | Convert an RSS or Atom feed into email newsletters. | `rss`, `newsletter`, `automation` |
| [Elements](https://github.com/unlayer/elements) | React components for transactional emails, landing pages, invoices and PDFs. | `email`, `react`, `templates` |
| [listmonk-rss](https://github.com/ping13/listmonk-rss) | Provides an RSS integration for listmonk, the self-hosted newsletter and mailing list manager. | `rss`, `listmonk`, `integration` |

## 🪄 Audience, Forms and Subscription Management

How subscribers get onto the list in the first place.

| Project | What it is | Tags |
|---|---|---|
| [formbricks](https://github.com/formbricks/formbricks) | Open source, self-hostable surveys and forms for collecting and qualifying signups. | `forms`, `surveys`, `self-hosted` |
| [lovecroft](https://github.com/thesephist/lovecroft) | Minimal mailing list manager for static sites, with a simple JSON API. | `mailing-list`, `static-sites`, `api` |
| [formzero](https://github.com/BohdanPetryshyn/formzero) | Form backend with zero paid features, deployable to a free Cloudflare account. | `forms`, `backend`, `cloudflare` |

## 🔁 Marketing Automation and CRM-Adjacent

What a list turns into once you want segmentation, journeys and a record of who the reader is.

| Project | What it is | Tags |
|---|---|---|
| [mautic](https://github.com/mautic/mautic) | Open source marketing automation software with campaigns, segments and forms. | `marketing-automation`, `crm`, `php` |
| [dittofeed](https://github.com/dittofeed/dittofeed) | Open-source customer engagement: automate transactional and marketing messages across email, SMS and push. | `marketing-automation`, `email`, `journeys` |
| [django-crm](https://github.com/DjangoCRM/django-crm) | CRM and task management software with email marketing built in. | `crm`, `email-marketing`, `django` |

---

## About this list

- **30** entries across **5** sections.
- Compiled from public sources; every linked project carries its own license.
- Last updated: **2026-10-17**.
- Data lives in `data/content.json` — this README is generated, do not edit by hand.

## License

The text and curation in this repository are licensed under CC BY 4.0. Linked projects keep their own licenses.
