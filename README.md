# Table 20-138 Record

An index of public records of the City of San José showing when the use "Social service agency" entered the City's zoning tables, when it entered the Mixed Use Commercial (MUC) district, and when it left the published table (San José Municipal Code §20.55.203, Table 20-138).

Every statement on the page is taken from a document linked beside it. The page states no conclusions. Not legal advice.

- `index.html` — the page (self-contained; no external dependencies except two Google Fonts, which degrade gracefully).
- `docs/` — the source documents. SHA-256 hashes of every file are listed on the page under *Documents*.
- The Zoning Districts GeoJSON (86 MB) is not included; its hash and feature count are in the summary CSV under `docs/`.

Sources: City Clerk ordinance archive (records.sanjoseca.gov), Municode (library.municode.com/ca/san_jose), sanjose.legistar.com, the Planning Commission agendas page at sanjoseca.gov, the California Public Notice database, and the City's ArcGIS services.

To publish on GitHub Pages: create a public repository, upload these files at the repository root, then Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`. The site appears at `https://<user>.github.io/<repo>/` within a few minutes.
