# Calculator-

## Project

Two plain HTML/CSS calculator practice pages:

- `calcu.html`: a numeric keypad and calculator display layout.
- `cal_home.html`: a calculator-themed launcher page.

No calculation JavaScript is included. The launcher's existing `cal_js.html` target is absent from this repository. Existing titles, layouts, controls and image assets are preserved.

Serve the directory with a static web server and open either HTML file to preview it. No package manifest, configured lint suite or build command is present.

## Metadata and attribution

Both pages include descriptions, TheBenzzCreations author/creator metadata, Open Graph metadata and Twitter card metadata. Descriptions identify the project as a layout exercise rather than claiming working calculation features.

`calcu.html` includes one WebPage JSON-LD block identifying the creator and one visible developer credit beneath the calculator layout. The developer link uses a normal same-tab hyperlink.

Production identity is recorded in `seo-sites.json`; see Canonical URL validation below. The developer credit is not evidence of a project deployment URL.

## Development & Maintenance

**Developed & Maintained by
[Khushal Sehrawat](https://github.com/khushalsehrawat)**
— Founder of
[TheBenzzCreations](https://www.thebenzzcreations.com/).

TheBenzzCreations is a digital development studio specializing in website development, custom software, mobile applications, e-commerce solutions and AI-powered business automation.

For development enquiries and collaborations, visit [TheBenzzCreations](https://www.thebenzzcreations.com/).

## Canonical URL validation

Run `python scripts/validate_seo.py` from this repository before publishing. The dependency-free check validates exact page canonicals, Open Graph URLs, website/application JSON-LD URLs, sitemap locations, robots sitemap references and literal framework site metadata against `seo-sites.json`. It checks deployment path prefixes as well as domains, so one GitHub Pages project cannot canonicalize to another.

Only URLs whose live HTML matched the local page on 2026-11-21 are configured. Unverified pages have no canonical or social URL; `python scripts/validate_seo.py --require-verified` also fails for those pending pages. Reverify the configuration if the deployment moves. Dynamic framework expressions still require runtime validation.

TheBenzzCreations attribution, creator organization URLs and existing normal same-tab developer credit links are preserved. These outbound attribution links are separate from site identity.
