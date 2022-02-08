# App Store Connect OpenAPI Spec

- Download: [Latest spec](/specs/latest.json)
- Should match: [Apple download](https://developer.apple.com/sample-code/app-store-connect/app-store-connect-openapi-specification.zip)

Automatically tracks every copy of the App Store Connect OpenAPI JSON Spec.
Apple does not appear to keep a list of every instance of the OpenAPI schema so it's hard to determine diffs across versions.
This project runs a cron job in GitHub Actions to download the [generic link](https://developer.apple.com/sample-code/app-store-connect/app-store-connect-openapi-specification.zip) and open a PR with the latest spec if it changes.

This repo is also seeded with various versions I've collected manually.
