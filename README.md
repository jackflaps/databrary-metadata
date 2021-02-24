# metadata

Information about mapping to published open schemas and ontologies.

## Goals

1. Make Databrary compliant with open data schema standards, wherever possible.
    - [NIH Common Data Elements (CDE)](https://cde.nlm.nih.gov/home). High priority.
    - [DataCite](https://datacite.org/). High priority.
    - [Schema.org](https://schema.org/). High priority.
    - [JSON-LD](https://json-ld.org/). High priority.
    - [DataTags](http://datatags.org/) project at [Harvard](https://privacytools.seas.harvard.edu/datatags) project. Moderate priority.
    - [Cognitive Atlas](https://www.cognitiveatlas.org/). Low priority.
2. Support users who want to provide data compatible with these standards to do so in straightforward ways that enable self-curation.
3. Support linking data elements to specific, version-controlled, data schemas.
4. Eventually, support linking data sets or projects to concepts, tasks, disorders, or theories defined on [Cognitive Atlas](https://www.cognitiveatlas.org/) using the [Cognitive Atlas API](https://www.cognitiveatlas.org/api).

## Documents

- [NIH CDE and Databrary 1.0/PLAY Project](nih-cde.md).
- [Google sheet](https://docs.google.com/spreadsheets/d/1-WbbMmRPxhszbBBA4qLrlyBBq4uGv_aWtf41-KFd32k/edit#gid=1060571672) mapping existing most Databrary data elements and API calls to schema.org and datacite.org.
- Current Databrary 1.0 schema specifications
    - [Volume](https://github.com/databrary/curation/blob/master/spec/volume.json) (will be called `project` in Databrary 2.0) specification.
    - [Metadata](https://github.com/databrary/curation/blob/master/spec/metadata.md) requirements for automated (not self-curated) ingest of data into Databrary 1.0.

## Tools

- [`databraryapi`](https://github.com/PLAY-behaviorome/databraryapi) R package.
    - There is a [Python version](https://github.com/PLAY-behaviorome/databrarypy) that is less well developed.
- Internal [Databrary reports](https://gilmore-lab.github.io/databrary-analytics/) that use the `databraryapi` package.
    - [Which volumes/projects](https://gilmore-lab.github.io/databrary-analytics/shared-volumes-sessions/shared-volumes-sessions.html) have shared sessions and of what type (overview only or full volume)?
    - [What user-defined tags or keywords](https://gilmore-lab.github.io/databrary-analytics/tags-keywords/tags-keywords-report.html) have been added to volumes/projects?
    - What [types of files](https://gilmore-lab.github.io/databrary-analytics/volumes-with-videos-annotations/assets-stats.html) have been shared?
    - What volumes/projects provide [demographic data](https://gilmore-lab.github.io/databrary-analytics/participant-demographics/participant-demog-report.html) about individual participants using the Databrary spreadsheet?
    - Data about which [shared projects have indicated funding sources](https://gilmore-lab.github.io/databrary-analytics/funders/funder-report.html).
