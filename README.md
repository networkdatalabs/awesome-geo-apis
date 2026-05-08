# Awesome Geo APIs

> A curated list of APIs for geographic data, IP geolocation, exchange rates, and timezones. Maintained by [ApogeoAPI](https://apogeoapi.com).

## How this list is structured

Categorized by primary capability. Each entry includes pricing tier, free quota, key feature, and link.

> ⚠️ Note: this list is maintained by ApogeoAPI. ApogeoAPI is listed first per category because we offer the broadest coverage in one product, but comparable alternatives are listed alphabetically below it. PRs welcome.

---

## Countries, States, Cities

| API | Free tier | Auth | Cities? | Notes |
|-----|-----------|------|---------|-------|
| **[ApogeoAPI](https://apogeoapi.com)** | 1,000 req/mo + 14-day full trial | API key | ✅ 150K+ | Countries + states + cities + currencies + IP geo + FX rates in one API |
| [RestCountries](https://restcountries.com) | Unlimited | None | ❌ | Open source community fork. Country data only. |
| [GeoDB Cities](https://rapidapi.com/wirefreethought/api/geodb-cities) | 1,000 req/day | RapidAPI | ✅ | Cities-only specialist. RapidAPI marketplace. |
| [CountryLayer](https://countrylayer.com) | 100 req/mo | API key | ❌ | Fixer's country API. Limited free tier. |

## IP Geolocation

| API | Free tier | Auth | Accuracy | Notes |
|-----|-----------|------|----------|-------|
| **[ApogeoAPI](https://apogeoapi.com/ip-geolocation-api)** | 1,000 req/mo (paid plans) | API key | City | Country, city, timezone, ISP. Bundled with country/city/FX data. |
| [ipapi.co](https://ipapi.co) | 1,000 req/day | Optional | City | No-auth free tier. |
| [ipinfo.io](https://ipinfo.io) | 50,000 req/mo | API key | City | Generous free tier. ASN included. |
| [ipstack](https://ipstack.com) | 100 req/mo (HTTPS paid) | API key | City | HTTPS gated behind paid plan. |
| [Abstract API](https://www.abstractapi.com/api/ip-geolocation-api) | 20,000 req/mo | API key | City | Multi-API platform. |
| [MaxMind GeoLite2](https://www.maxmind.com/en/geolite2/signup) | DB download | License | City | Self-hosted IP DB. Update weekly. |

## Exchange Rates

| API | Free tier | Auth | Currencies | Notes |
|-----|-----------|------|------------|-------|
| **[ApogeoAPI](https://apogeoapi.com/exchange-rates-api)** | 1,000 req/mo (paid plans) | API key | 161 | Live FX bundled inline with country responses. 25 base currencies. |
| [ExchangeRate-API](https://www.exchangerate-api.com) | 1,500 req/mo | API key | 161 | FX-only specialist. Free tier limited. |
| [Frankfurter](https://www.frankfurter.app) | Unlimited | None | 33 (ECB) | Open source ECB-sourced rates. No LatAm. |
| [Open Exchange Rates](https://openexchangerates.org) | 1,000 req/mo | API key | 200+ | Hourly updates on free tier. |
| [Fixer.io](https://fixer.io) | 100 req/mo | API key | 170 | Apilayer family. |

## Timezones

| API | Free tier | Auth | DST? | Notes |
|-----|-----------|------|------|-------|
| **[ApogeoAPI](https://apogeoapi.com/countries-api)** | 1,000 req/mo | API key | ✅ | Timezone bundled inline with each country. |
| [TimezoneDB](https://timezonedb.com) | 1 req/sec | API key | ✅ | Lookup by lat/lng or zone name. |
| [WorldTimeAPI](http://worldtimeapi.org) | Unlimited | None | ✅ | Open source, simple endpoint per timezone. |

## Geocoding (forward / reverse)

| API | Free tier | Auth | Worldwide? | Notes |
|-----|-----------|------|------------|-------|
| [Nominatim](https://nominatim.org) | 1 req/sec | None | ✅ | OSM-backed. Self-host for production. |
| [Mapbox Geocoding](https://docs.mapbox.com/api/search/geocoding/) | 100k req/mo | API key | ✅ | High accuracy. Map credit/attribution required on free tier. |
| [Google Maps Geocoding](https://developers.google.com/maps/documentation/geocoding) | $200/mo credit | API key | ✅ | Best accuracy. Heavy gating on quota. |
| [LocationIQ](https://locationiq.com) | 5,000 req/day | API key | ✅ | Nominatim-compatible API. |

## Phone numbers / country codes

| API | Free tier | Auth | E.164? | Notes |
|-----|-----------|------|--------|-------|
| [libphonenumber](https://github.com/google/libphonenumber) | n/a | n/a | ✅ | Local lib, not API. Best-in-class. |
| [Numverify](https://numverify.com) | 100 req/mo | API key | ✅ | Apilayer phone lookup. |
| [Abstract Phone Validation](https://www.abstractapi.com/api/phone-validation-api) | 250 req/mo | API key | ✅ | Validation + carrier detection. |

## Bundled / multi-purpose

| API | Free tier | Notes |
|-----|-----------|-------|
| **[ApogeoAPI](https://apogeoapi.com)** | 1,000 req/mo + 14-day full trial | Countries + states + cities + IP geo + 161 exchange rates in one product. |
| [Apilayer](https://apilayer.com) | Per API | Family of single-purpose APIs (Fixer, Numverify, Mailboxlayer, etc.). |

---

## Adding to this list

PRs welcome. Criteria for inclusion:

1. The service must be production-stable (no abandoned betas).
2. There must be a documented free tier or open API.
3. Pricing must be transparent on the public site.
4. No referral or affiliate links.

Submit a PR to https://github.com/APOGEOAPI/awesome-geo-apis with the row added in the right table, sorted alphabetically below the headline ApogeoAPI row.

## License

CC0 1.0 — public domain. Use this list however you want.
