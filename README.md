[![JSON Schema logo - Build more, break less, empower others.](https://raw.githubusercontent.com/json-schema-org/.github/main/assets/json-schema-banner.png)](https://json-schema.org)

<br/> 
<p>
    <a href="https://github.com/json-schema-org/website/graphs/contributors" alt="JSON Schema GitHub website contributors">
      <img src="https://img.shields.io/github/contributors/json-schema-org/website?color=orange" />
    </a>
    <a href="https://github.com/json-schema-org/website/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22" alt="Good First JSON Schema issue">
      <img src="https://img.shields.io/github/issues/json-schema-org/website/good%20first%20issue.svg?color=%23DDDD00" />
    </a>
    <a href="https://github.com/json-schema-org/.github/blob/main/CODE_OF_CONDUCT.md" alt="Contributor Covenant">
      <img src="https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg" />
    </a> 
    <a href="https://www.repostatus.org/#active" alt="Repo status">
      <img src="https://www.repostatus.org/badges/latest/active.svg" />
    </a> 
    <a href="https://json-schema.org/slack" alt="JSON Schema Slack">
      <img src="https://img.shields.io/badge/Slack-json--schema-@website.svg?logo=slack&color=yellow" />
    </a>   
</p>

# 👋 Welcome to the JSON Schema website
This repository contains the sources of JSON Schema website:

* It's powered by Next.js,
* It uses Tailwind CSS framework,
* It's build and deployed with Netlify.

## Setting up Project

Please refer to the [INSTALLATION.md](./INSTALLATION.md) file for instructions on how to set up the project on your local machine.

## Project structure

This repository has the following structure:

<!-- If you make any changes in the project structure, remember to update it. -->

```text
  ├── .github                     # Definitions of GitHub workflows, pull request and issue templates
  ├── components                  # Various generic components such as "Button", "Figure", etc.
  ├── data                        # JSON Schema Implementations.
  ├── styles                      # Various CSS files
  ├── lib                         # Various JS code for preparing static data to render in pages
  ├── pages                       # Website's pages source. It includes raw markdown files and React page templates.
  │    ├── overview               # JSON Schema initiative docs
  │    ├── blog                   # Blog posts
  │    ├── learn                  # JSON Schema docs
  │    └── implementations        # Various pages to describe tools
  ├── public                      # Data for site metadata and static blog such as images
  ├── next.config.js              # Next.js configuration file

```

## Contribute

Here are some areas where you can contribute to the website:
- Blogs posts
- Case Studies
- Design
- Documentation
- Website enhancements
- Add a new JSON Schema Implementation
- JSON Schema Landscape

To figure out a good first issue to work on, join our Slack workspace and visit the `#contribute` channel. This channel is specifically designed for onboarding and supporting new contributors.

You should also check out our [Contributing guidelines](./CONTRIBUTING.md).

### Contributors

Thanks goes to these wonderful people who contributed to this website:
<a href = "https://github.com/json-schema-org/website/graphs/contributors">
  <img src = "https://contrib.rocks/image?repo=json-schema-org/website"/>
</a>

<sub>Made with [contributors-img](https://contrib.rocks).</sub>

### Sponsors

[![Sponsors](https://opencollective.com/json-schema/sponsors.svg)](https://opencollective.com/json-schema/sponsors.svg?avatarHeight=90)

### Backers

**Thank you to all our backers!**
[![Backers](https://opencollective.com/json-schema/backers.svg)](https://opencollective.com/json-schema/backers.svg?avatarHeight=90)

## Connect with the JSON Schema Community

<p align="left">
    <a href="https://json-schema.org/slack" target="blank" style="margin-right: 5px;"><img align="center" src="https://img.icons8.com/color/48/null/slack-new.png" alt="JSON Schema Slack" height="30" width="40" /></a>
    <a href="https://x.com/jsonschema" target="blank" style="margin-right: 5px;"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="JSON Schema Twitter" height="30" width="40" /></a>
    <a href="https://www.linkedin.com/company/jsonschema" target="blank" style="margin-right: 5px;"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="JSON Schema LinkedIn" height="30" width="40" /></a>
    <a href="https://www.youtube.com/@JSONSchemaOrgOfficial" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="JSON Schema YouTube" height="30" width="40" /></a>
</p>

## Inspired by
This document has been inspired by [AsyncAPI website README.md](https://github.com/asyncapi/website/blob/master/README.md).

## License
The contents of this repository are [licensed under](./LICENSE) either the BSD 3-clause license *or* the Academic Free License v3.0.
