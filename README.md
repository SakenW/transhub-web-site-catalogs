# Trans-Hub Web Site Catalogs

This repository publishes immutable, self-curated canonical source catalogs
for Trans-Hub Web localization. Each GitHub Release asset is bound by the
public discovery executor to its exact release, commit, file name and SHA-256.

Catalogs contain only approved translation source units and context. They do
not contain web URLs, DOM, selectors, browser profiles, cookies or raw page
captures.

The trusted Web catalog executor resolves each site against the **latest**
stable Release. Each new Release must therefore contain the full approved site
set, including unchanged assets from earlier Releases. The JSON file under
`releases/` records the intended asset names, exact SHA-256 values and source
unit counts before an immutable Release is published. It is review evidence,
not a substitute for the GitHub Release assets or their server-side adoption.
