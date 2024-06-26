---
name: Major release
about: Create a new major release
title: New major release
assignees: "sesheta"
labels: bot
---

Hey, Kebechet!

Create a new major release, please.

**IMPORTANT NOTES**

- _If [Khebut GitHub App Bot](https://github.com/apps/khebhut) is installed, this issue will trigger a major release. The bot will open a Pull Request to update the CHANGELOG, fix the opened issue and create a tag._

- _Only users that are allowed to release (a.k.a. maintainers specified in the .thoth.yaml file) can open the issue, otherwise bot will reject them, commenting and closing the issue. If [AICoE CI GitHub App](https://github.com/apps/aicoe-ci) is installed, once the pull request is merged and a new tag is created by the bot, the pipeline to build and push image starts._
