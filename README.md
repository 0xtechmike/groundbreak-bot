# GroundbreakBot

If you've seen **`GroundbreakBot/1.0`** in your website or API logs, this page explains who we are and how to reach us.

## Who we are

Groundbreak (working name) is a small business-information service run by TechMinded. It tells local
business-to-business vendors (for example kitchen-equipment suppliers, sign makers and cleaning companies)
about new restaurants, commercial build-outs and construction projects in their area, using **public
records** such as building permits and alcohol-licence applications.

## What GroundbreakBot collects

- **Public records only:** permit and licence data that agencies publish for public use.
- **Official data services first:** open-data APIs (Socrata, ArcGIS, CKAN) and published bulk files. We read
  ordinary web pages only where `robots.txt` and the site's terms allow it.
- **No personal contact details:** we don't collect or look up homeowners' phone numbers or email addresses.

## How it behaves

- **Once a night, off-peak**, usually between 1 and 5 a.m. local time.
- **One request at a time per website**, with pauses between requests, and nothing re-fetched that hasn't changed.
- **Follows `robots.txt`** and each site's terms of use.
- **Slows down** when a server signals it's busy (HTTP 429 or 503).
- **Stops completely** if a site blocks it or asks it to stop. We never rotate IP addresses or proxies,
  disguise the bot as a browser, or try to get around a block.

## Contact us

**Email: [support@preribbon.com](mailto:support@preribbon.com)**

Please get in touch if you'd like us to:

- **stop or slow down** collection from your site (we'll pause it as soon as we see your message);
- use a **bulk export or other channel** that is easier for you;
- correct something, or ask any question about how we use your data.

## Identification

Every request carries this User-Agent:

```
GroundbreakBot/1.0 (+https://github.com/0xtechmike/groundbreak-bot; support@preribbon.com)
```
