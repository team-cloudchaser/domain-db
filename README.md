# Domain list database
Make your *ray instance a viable adblocker, on either servers or clients.

Build status: [![Build dlc.dat](https://github.com/ltgcgo/domain-db/actions/workflows/build.yml/badge.svg)](https://github.com/ltgcgo/domain-db/releases/latest/download/dlc.dat) (Click to download!)

This project was pulled and forked from `v2fly/domain-list-community`, with only its data changed to use several blocklists. Remote blocklists are automatically pulled and updated.

## Downloads

- **dlc.dat**：[GitHub Releases](https://github.com/ltgcgo/domain-db/releases/latest/download/dlc.dat)
- **dlc.dat.sha256sum**：[GitHub Releases](https://github.com/ltgcgo/domain-db/releases/latest/download/dlc.dat.sha256sum)

## Lists
### Route hints
- `condensed`: The deduplicated and condensed blocklist, from OISD Basic, 1Hosts Lite, Blocklist Project (ransomware), Blocklist Project (scam) and Phishing.Army.
- `grp-avhigh`: Suggested to be accessed only in regions without any age verification.
- `grp-avmid`: Suggested to be accessed only in regions without stringent age verification.
- `grp-avmid-hl`: Suggested to be accessed only in regions without stringent age verification. The tunnel should be of high load.
- `list-adjacent`: Suggested to be accessed without additional exit tunnels, only when the exit tunnel is geographically adjacent.
- `list-freedom`: Suggested to be accessed without additional exit tunnels.
- `list-tor`: Suggested to be accessed via Tor exit nodes.

### Geoblock hints
- `geo-at`: Geoblocked services in Austria.
- `geo-de`: Geoblocked services in Germany.
- `geo-fr`: Geoblocked services in France.
- `geo-jp`: Geoblocked services in Japan.
- `geo-nl`: Geoblocked services in the Netherlands.
- `geo-no`: Geoblocked services in Norway.
- `geo-ru`: Geoblocked services in Russia. It's recommended to block access to these domains on servers instead.
- `geo-us`: Geoblocked services in the United States.
- `geo-uk`: Geoblocked services in the United Kingdom.
- `grp-de`: Geoblocked services in German-speaking regions (e.g. Germany, Austria, Switzerland).
- `grp-frde`: Joint Franco-German services, accessible only in France and Germany (e.g. Arte).
- `grp-ukie`: Joint British and Irish services, accessible only in the UK and Ireland.

### Geographic hints
- `ir`: Iranian websites.

### Services
- `tiktok`: List of TikTok domains.