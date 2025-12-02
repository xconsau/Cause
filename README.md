----

# Cause (Variable)

[![][Fontspector]](https://xconsau.github.io/Cause/fontspector/fontspector-report.html)
[![][OpenType]](https://xconsau.github.io/Cause/fontspector/fontspector-report.html)
[![][Universal]](https://xconsau.github.io/Cause/fontspector/fontspector-report.html)
[![][Google Fonts]](https://xconsau.github.io/Cause/fontspector/fontspector-report.html)
[![][Glyphset]](https://xconsau.github.io/Cause/fontspector/fontspector-report.html)

[Fontspector]: https://img.shields.io/endpoint?url=https%3A%2F%2Fxconsau.github.io%2FCause%2Fbadges%2FFontspectorQA.json
[OpenType]: https://img.shields.io/endpoint?url=https%3A%2F%2Fxconsau.github.io%2FCause%2Fbadges%2FOpentypeSpecificationChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fxconsau.github.io%2FCause%2Fbadges%2FUniversalProfileChecks.json
[Google Fonts]: https://img.shields.io/endpoint?url=https%3A%2F%2Fxconsau.github.io%2FCause%2Fbadges%2FFontFileChecks.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fxconsau.github.io%2FCause%2Fbadges%2FOutlineCorrectnessChecks.json
[Glyphset]: https://img.shields.io/endpoint?url=https%3A%2F%2Fxconsau.github.io%2FCause%2Fbadges%2FGlyphsetChecks.json

'Cause' is a semi-casual, optimistic sans-serif typeface crafted to support the communication needs of non-profit organizations, educational institutions, environmental initiatives, and learning-focused applications.

The design follows a clean monolinear construction with gently rounded terminals, offering a balance of warmth and clarity. It was created to address a recurring design need: a typeface that feels friendly and approachable without drifting into a comic or overly playful tone&mdash;capable of delivering serious messages with comfort and ease. This makes it particularly suitable for projects in education, social impact, food and lifestyle blogging, environmental advocacy, and various forms of children&rsquo;s communication materials.


![Sample Image](documentation/article/c1.png)
![Sample Image](documentation/article/c2.png)
![Sample Image](documentation/article/c3.png)
![Sample Image](documentation/article/c4.png)
![Sample Image](documentation/article/c5.png)
![Sample Image](documentation/article/c6.jpg)

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at `https://yourname.github.io/your-font-repository-name`.

## Changelog

**11 Apr 2024. Version 0.1**
- Initial release

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
