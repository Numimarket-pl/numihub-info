# NumiHub

NumiHub is an internal application used by Numimarket.pl to support operational workflows and marketplace integrations.

This page identifies the NumiHub application for Allegro REST API traffic.

## Owner

- Service: [numimarket.pl](https://numimarket.pl)
- Application owner: Numimarket.pl
- Contact: [numimarket.pl/kontakt](https://numimarket.pl/kontakt)
- Information page: [github.com/Numimarket-pl/numihub-info](https://github.com/Numimarket-pl/numihub-info)

## Allegro API Usage

NumiHub uses the Allegro API for authorized Allegro accounts to support basic business processes, including:

- synchronizing offer information,
- synchronizing order information,
- reading Allegro category data for internal category mapping.

The application uses Allegro API access only for internal operational purposes and authorized Allegro accounts.

## User-Agent

Requests made by NumiHub to the Allegro API are identified with the following custom `User-Agent` header:

```text
numihub_dev/2026.06.27 (+https://github.com/Numimarket-pl/numihub-info)
```

## Repository Purpose

This repository is a public informational page for identifying the NumiHub application in Allegro API traffic.

It does not contain the application source code.
