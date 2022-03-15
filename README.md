# Mat Moore

I'm a senior technologist with expertise in Ruby, Python and Java. I help teams to deliver faster and address technical debt.

[**Contact me about working together**](https://github.com/MatMoore/MatMoore/issues/new?assignees=MatMoore&labels=&template=contact-me.md&title=Working+together)

## My projects
Here are a few examples of my work online. For more projects, see my website at https://matmoore.github.io/

### (2020) List of online board games and party games
- Viewable at: https://matmoore.github.io/online-board-games-and-party-games/
- Blog post: [A list of board games and party games you can play online](https://dev.to/matmooredev/a-list-of-board-games-and-party-games-you-can-play-online-4741)

I created this site at the start of the pandemic to track websites where you can play tabletop games remotely and since then have gathered many online games, platforms and print & play games. I used github pages to make it as easy as possible to contribute to. 

### (2020) COVID API (no longer active)
- Source code: [andreagrandi/covid-api](https://github.com/andreagrandi/covid-api)

In early 2020 I collaborated with [@andreagrandi](https://github.com/andreagrandi) to wrangle public data about COVID rates into an API, using python and fastapi. This project was a good reminder of how important data collection and curation is when relying on data for anything important.

During this early phase of the pandemic, countries were scrambling to report any data at all, and there was a lot of typos and unreliable classification creeping in due to manual processing of the data. Even Johns Hopkins CSSE, the source of many figures reported in the news at the time, was publishing data with a lot of errors in it, and when we were working on this API they were often changing the schema to accomodate more and more granualar information (e.g. moving from country-level to county-level and starting to code the source of the statistics instead of relying on free text).

As the pandemic continued, the ways of detecting COVID changed, and countries changed what was reported, and who gets counted in the statistics, so our code is now out of date.

### (2019) Replatforming services for the legal aid agency
- [Prototype deployment pipeline for LAA services](https://github.com/ministryofjustice/deployment-pipeline-hello-world)
- [LAA-NOLASA](https://github.com/ministryofjustice/laa-nolasa/pulls?q=is%3Apr+is%3Aclosed+author%3AMatMoore) - a more recent service we were able to open source

I worked with teams at the Ministry of Justice to modernise and replatform legacy services in AWS. These applications were critical pieces of the legal aid system but had a very low satisfaction rate amongst users due to the poor user experience and frequent downtime.

I mainly focused on reducing the cycle time to making changes to the system, as developers were hampered by inadequate development and testing environments and a slow manual deployment process. As part of this work I helped to introduce continuous integration with automated checks, gradle, docker and terraform.
