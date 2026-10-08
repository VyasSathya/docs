# buildwhatever documentation

The MDX documentation source for buildwhatever. This repository contains guides and reference pages, with navigation, branding, and page groups defined in [docs.json](docs.json). It does not contain the application implementation.

## Find a page

| Area | Source |
| --- | --- |
| Introduction | [index.mdx](index.mdx) |
| Quickstart | [quickstart.mdx](quickstart.mdx) |
| Account and workspace setup | [getting-started/](getting-started/) |
| Nodes and integrations | [guides/](guides/) |
| API reference | [api-reference/overview.mdx](api-reference/overview.mdx) |
| Changes and beta notes | [changelog.mdx](changelog.mdx), [beta/](beta/) |

## Edit the documentation

1. Edit a page's MDX content and its frontmatter title and description.
2. For a new page, add its extensionless path to the appropriate navigation group in `docs.json`.
3. Keep logos and page artwork in [images/](images/).
4. Check relative page links and the documented product behavior before publishing.

The configuration uses the Mintlify `docs.json` schema and its `mint` theme. This checkout does not include a local preview command, dependency manifest, or publishing workflow, so a reproducible preview setup still needs to be documented.

## Status

The repository records product documentation and beta notes. External app links, API examples, advertised CLI/extension availability, and deployment instructions require verification against the product release they describe. No live deployment or API behavior was validated during this documentation review.

## License

No license file is included in this repository.
