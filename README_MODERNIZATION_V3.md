# Veterans Career & Resource Hub v3

Replace these files in:

`vervenveda/veterans.github.io`

with the included versions:

- `index.html`
- `mentor-manifest.json`
- `docs/RESOURCE_RESEARCH.md`

## Primary modernization

The Veterans page is now career-transition first:

1. Discover Direction
2. Translate Service
3. Build the Professional Package
4. Train & Credential
5. Enter the Market
6. Build a Business

The existing **One Door · No Wrong Door** public-service principle remains intact.

## VNV consistency

The page now uses the same shared ecosystem shell:
- 36px network ticker
- 72px light sticky header
- breadcrumbs
- searchable right-side directory
- paper / forest / gold / navy visual system
- 7px and 11px interface radii

## Career integration

Direct integration now points to:
- `https://vervenveda.com/Khaemenes_Higher_Learning.github.io/Career/`
- `https://vervenveda.com/Khaemenes_Higher_Learning.github.io/`
- `https://vervenveda.com/proresource_hub.github.io/`

The obsolete internal Career Star path under `Khaemenes_Academy.github.io/higher_learming/...` is removed.

## Military Skills Translation Notebook

Local-only storage keys:
- `vnv-veterans-career-translation-v1`
- `vnv-veterans-career-mission-progress-v1`

The notebook supports:
- service branch/component
- MOS/rating/AFSC/role
- responsibilities translated into civilian language
- transferable skills
- civilian-safe credentials
- civilian roles to explore
- education/credential gaps
- local save
- JSON export
- mission-progress checklist

The interface explicitly prohibits classified, sensitive operational, medical, identity, claims, and credential-secret information.

## Dynamic professional directory

The Professional Tools section reads:

`https://vervenveda.com/assessment-engine/mentor/registry/ecosystem-resources.json`

It dynamically surfaces eligible career, professional-writing, business, finance, technology, design, research, and workplace-productivity resources.

Official government veteran resources remain curated separately because those are freshness-sensitive and potentially high stakes.

## Updated mentor manifest

The previous manifest was a provisional root-only federation anchor.

Version 2 now exposes:
- Veterans Hub
- Career Mission
- Skills Translation Notebook
- Employment Launch
- Education & Training
- Veteran Entrepreneurship
- Official Resource Directory

## Nearby support

The optional location helper:
- never requests location on page load
- stores coordinates only in JavaScript memory for the current tab
- supports manual city/state/ZIP entry
- does not save location to localStorage

## Existing service coverage retained

Career is the primary path, while official links remain for:
- benefits
- records
- health
- mental health / PTSD
- housing
- family/caregivers
- legal/claims support
- state veterans offices
- VA locations
