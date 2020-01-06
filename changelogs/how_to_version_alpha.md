# How to version alpha

Whenever we push to Janis or Joplin to production, we must specify a new version. This project kinda adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) but with these changes:

- Update major version x.\_.\_ whenever we decide that we're at version 3.
- Update minor version \_.x.\_ whenever there's a breaking change that requires updates to both Janis and Joplin. Minor + patch versions of Janis and Joplin should *always* be compatible with each other.
- Update patch version \_.\_.x whenever there's a change to one repo that does not also require a change to the other repo.

For each update make sure to include a table with this information.

|||
|-|-|
| **Date** | The date of the production push   |
| **PR link**  | A link to the PR into production |
| **Latest Commit Hash** | The hash of the final commit |
| **Stable?**  | Default to "y". Retroactively change this to "n" with an explanation if there was a breaking change/severe regression. The subsequent hotfix will then be submitted as a new version. |

Then add a brief sentence for each new feature that's included in your version. Follow the [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) format to the best of your ability. But be sure to include a link to the Issue for every added feature/fix/update.

Main repos <!-- keep this up to date if it changes!! -->:
- [https://github.com/cityofaustin/janis](https://github.com/cityofaustin/janis)
- [https://github.com/cityofaustin/joplin](https://github.com/cityofaustin/joplin)

And Friends:
- https://github.com/cityofaustin/django-countable-field
- https://github.com/cityofaustin/wagtail-modeltranslation
- https://github.com/cityofaustin/publisher
- https://github.com/cityofaustin/coa-joplin-clean-up
