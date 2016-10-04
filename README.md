# Standard RAML Annotations Repository

> This repository contains annotations that we, as a community, agreed on and share for others to use.

## Introduction

With RAML 1.0, we can extend the specification with additional metadata without breaking the RAML validation. That gives us the chance to build in tooling or processing specific information, or just more documentation. This repository collects all annotations that, so far, has been discussed and agreed upon inside the community. Everyone can use them, and identify which tools do support a particular annotation by browsing the list of issues.

All annotations will regularly be reviewed by the RAML Workgroup to identify potential candidates for the next version of RAML. It gives the community another channel to contribute ideas and improve the RAML specification we all love.

## How can I contribute?

We welcome any contributions from the community! You can add new annotations by sending a PR, adding your annotation as a RAML fragment (see code below), and the community / contributors will review before we merge it to the repository. The following needs to be committed with each PR:

1. A RAML fragment that contains enough information to identify the purpose and use for the annotation. It needs to cover all necessary information that someone else quickly understands how and where the annotation can be used. All fragments needs to start with `#%RAML 1.0 AnnotationTypeDeclaration`.

2. Create an issue, explaining your annotation and what tools currently support that.

If you just have an idea for an annotation, but not sure what to do; still start a PR with the initial structure and begin a conversation to gather input.

## How can I upvote or give feedback to specific annotations?

Each contribution will encompass a PR and issue that people can use to help improving or to vote. Voting, in this case, will help the RAML Workgroup to identify new candidates better.

On PR's, you can discuss the annotations before they get merged. Whereas on an issue, you will be able to vote (simply add the Thumb's Up Emoji) or ask for updates / new additions. Any `+1` as a comment will be removed :P
