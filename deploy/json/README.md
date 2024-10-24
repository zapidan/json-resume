# JSON Deployment
As stated in the [README](../../README.md), a `resume.json` gist will be automatically deployed to https://registry.jsonresume.org/zapidan and you can add a theme parameter (see [themes](../../themes.md)).

## Instructions
Add your final version of `resume.json` to this folder. This can be a new file, but it is recommended that it's source controled in the [jsons versions directory](../../jsons).

A github action will automatically replace your `resume.json` gist, and this will make it available on https://registry.jsonresume.org/zapidan

**Note**: the json is rendered on the server, so only supported themes that are installed will be available (see [available themes](https://registry.jsonresume.org/themes))