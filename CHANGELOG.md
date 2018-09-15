# Documenter.jl changelog

## Version `v0.20-dev`

* ![BREAKING][badge-breaking] `makedocs` will now build Documenter's native HTML output by default. The default value of the `format` keyword has been changed to `:html`. ([#826][github-826])

  **For upgrading:** If you are relying on the Markdown output, you now need to set
  `format = :markdown` explicitly on `makedocs`.

  If you already specify the `format` keyword, then you do not need to make any changes.
  However, if are setting `format = :html`, you may remove that and rely on the new default.

* ![BREAKING][badge-breaking] "Pretty URLs" are enabled by default now for the HTML output. The default value of the `html_prettyurls` has been changed to `true`.

  For a page `foo/page.md` Documenter now generates `foo/page/index.html`, instead of `foo/page.html`.
  On GitHub pages deployments it means that your URLs look like  `foo/page/` instead of `foo/page.html`.

  Pretty URLs mean The HTML output now creates a `foo/page.md` results in `foo/page/index.html`

  Also, for local builds you should set
  `html_prettyurls = false`

  **For upgrading:** If you wish to retain the old behavior, set `html_prettyurls = false` in `makedocs`. If you already set `html_prettyurls`, you do not need to change anything.

* ![Enhancement][badge-enhancement] If Documenter is not able to determine which Git hosting service is being used to host the source of documentation, the "Edit on XXX" links become "Edit source" with a generic icon. ([#804][github-804])

[github-804]: https://github.com/JuliaDocs/Documenter.jl/pull/804
[github-826]: https://github.com/JuliaDocs/Documenter.jl/pull/826

Badges:
![BREAKING][badge-breaking]
![Deprecation][badge-deprecation]
![Feature][badge-feature]
![Enhancement][badge-enhancement]
![Bugfix][badge-bugfix]

[badge-breaking]: https://img.shields.io/badge/BREAKING-red.svg
[badge-deprecation]: https://img.shields.io/badge/deprecation-red.svg
[badge-feature]: https://img.shields.io/badge/feature-green.svg
[badge-enhancement]: https://img.shields.io/badge/enhancement-blue.svg
[badge-bugfix]: https://img.shields.io/badge/bugfix-purple.svg
